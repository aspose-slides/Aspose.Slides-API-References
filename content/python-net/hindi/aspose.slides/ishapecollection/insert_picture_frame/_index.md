---
title: insert_picture_frame method
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ishapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
निर्दिष्ट छवि को सम्मिलित करता हुआ एक नया चित्र फ्रेम बनाता है और इसे shape
            collection में निर्दिष्ट इंडेक्स पर सम्मिलित करता है।

### वापसी

नया बनाया गया [`IPictureFrame`](/slides/python-net/hi/aspose.slides/ipictureframe).



```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | चित्र फ्रेम डालने के लिए शून्य-आधारित इंडेक्स। |
| shape_type | [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype) में मौजूद shape type को निर्दिष्ट करता है,<br/><br/>            सभी प्रकार की रेखाओं को छोड़कर:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | चित्र फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | चित्र फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | चित्र फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | चित्र फ्रेम की ऊँचाई, पॉइंट्स में। |
| image | [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage) को चित्र फ्रेम में प्रदर्शित करने के लिए। |



### संबंधित देखें
* class [`IPictureFrame`](/slides/python-net/hi/aspose.slides/ipictureframe)
* class [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage)
* class [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)