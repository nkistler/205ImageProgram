#!/usr/bin/python
import re, os
from PIL import Image

def rotateCollage():
    inputDir = raw_input("Please enter directory: ")
    print "you entered", inputDir
    dirEntries = os.listdir("/" + inputDir)
    docNumber = 0
    docList = []
    size = 2816, 2112
    angle = 0
    imageName = re.sub(r'/', r'', cmmnd)
    im = Image.new("RGBA", size, "white")
    for entry in dirEntries:
    	if re.search(r'.jpg', entry):
	    docList.insert(docNumber, entry)
	    docNumber=docNumber+1
            angle=angle+20
            nextIm = Image.open(docList[docNumber-1])
            rotIm = nextIm.rotate(angle, expand=0)
            im.paste(rotIm, (0, 0))
        im.save(imageName + '.jpg')
    return

def createThumbnails():
    inputDir = raw_input("Please enter directory: ")
    print "you entered", inputDir
    dirEntries = os.listdir("/" + inputDir)
    return

def convertToBW():
    inputFile = raw_input("Please enter file: ")
    print "you entered", inputFile
    dirEntries = os.listdir("/" + inputFile)
    return

selection = ""
while selection.strip() != 'quit':
    print "Press 1 to rotate images"
    print "Press 2 to create image thumbnails"
    print "Press 3 to create black and white copies"
    selection = raw_input("Please enter command: ")
    print "you entered", selection
    if selection=="1":
        rotateCollage()
    if selection=="2":
        createThumbnails()
    if selection=="3":
        convertToBW()
    
            




