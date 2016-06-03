This project includes a script that uses reflection to extract
blender's python API from a running instance of blender and store it
in .py files usable by the pycharm IDE to aid in code completion.

This source code is derived from pydev-blender.zip at
http://airplanes3d.net/pydev-000_e.xml

First: generate a fresh set of skeletons using ./refresh_python_api
(which simply invokes python_api/pypredef_gen.py inside blender)

Then you can add the python_api/pypredef directory to pycharm's
interpreter using the screenshot pycharm-3.4-screenshot.png and the
instructions at http://stackoverflow.com/a/24206781/995935

If you do not want to add the blender API stubs to all your pycharm
projects you can simply add the python_api/pypredef directory to your
Project Structure.

https://www.blender.org/download/

https://www.jetbrains.com/pycharm/
