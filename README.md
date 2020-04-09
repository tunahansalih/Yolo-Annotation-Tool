# Yolo-Annotation-Tool

Do steps:

Before starting annotation, put image folder into the Images folder. Let my image folder name be `pics`, Project folder should be like this:
```
-main.py
-process.py
-classes.txt
-Images/
  -pics/
    -<image1>.png
    -<image2>.png
    -<image3>.png
    -...
-Labels/
  -pics/
```

Run below code with Python3
```
main.py
```

After running main.py, specify the image folder name that you put into `Images` folder. Just type `pics` into the `Image Dir` text box.

Before annotating bounding bozes choose which class to annotate.

After finishing annotating all images, run below file with Python3

```
process.py
```

The dataset is ready for yolo training.
