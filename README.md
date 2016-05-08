# FaceRecAttendanceUpdater

This is an application made to take attendance of students in class by using Face Recognition in OpenCV and Python.

The app has a database of faces of all the students in a class. It captures the faces of students when they enter class and

matches it with the faces in the database. If a match is found with a good confidence level, then attendance of the

corresponding student is updated.

The currently available algorithms for Face Recognition are:
* Eigenfaces
* Fisherfaces
* Local Binary Patterns Histograms ( LBPH )

Among these algorithms, we have implemented Eigenfaces.

To run the app, clone this repository and run the following command in the repo folder:

    $ /usr/bin/python __main__.py
