---
title: add_picture_frame method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/shapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
निर्दिष्ट छवि को शामिल करने वाला नया चित्र फ़्रेम बनाता है और इसे shape संग्रह के अंत में जोड़ता है।

### रिटर्न

नया बनाया गया [`IPictureFrame`](/slides/python-net/hi/aspose.slides/ipictureframe).



```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype) | निर्दिष्ट करता है कि [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype) में कौन सा shape प्रकार शामिल है,<br/><br/>            सभी प्रकार की लाइनों को छोड़कर:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | चित्र फ़्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | चित्र फ़्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | चित्र फ़्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | चित्र फ़्रेम की ऊँचाई, पॉइंट्स में। |
| image | [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage) | चित्र फ़्रेम में प्रदर्शित करने के लिए [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage)। |



### देखें
* कक्षा [`IPictureFrame`](/slides/python-net/hi/aspose.slides/ipictureframe)
* कक्षा [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage)
* कक्षा [`ShapeCollection`](/slides/python-net/hi/aspose.slides/shapecollection)
* एन्यूमरेशन [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)