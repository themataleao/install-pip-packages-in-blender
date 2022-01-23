# install-pip-packages-in-blender (Linux)

# Short explenation how to install python packages within the blender environment

1. Open blender
2. Go to the scriptiong section
3. Within the console type:
   ```python
   import sys
   sys.exec_prefix
   ```
4. Go the given path (in my case it was `'/snap/blender/1237/3.0/python'`)
5. Then you run `./bin/python3.9 -m ensurepip` to ensure pip is installed
6. Now you run installations with `./bin/python3.9 -m pip install your_package_name`
