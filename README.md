# maya_combineSeparate

A python module for Autodesk Maya that shows tha way to collect objects data before combining them and allowing to separate a new combined object back to original ones

It uses standart python libraries, maya.cmds, maya.mel and maya.OpenMaya

Future plans:
 -Lets users to combine selected objects, assign a skin cluster and adjust the weights and finally to separate back to original objects saving the skinning.
 
 
Using:

Unzip the project to your Maya Python path folder
 
import combineSeparate.combineSeparate as cmbSep

instance = cmbSep()
 
#select some objects
 
instance.doCombine() #to combine objects

instance.doSeparate() #to separate back to original objects
 
 
 Vendor: Roman Volodin
 
 website: http://romanvolodin.com
 
 email: contact@romanvolodin.com
 
 2015
