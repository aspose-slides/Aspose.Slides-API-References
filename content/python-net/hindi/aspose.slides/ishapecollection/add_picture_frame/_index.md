---
title: add_picture_frame method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ishapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
निर्दिष्ट छवि को सम्मिलित करते हुए एक नया चित्र फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।

### रिटर्न
नया बनाया गया [`IPictureFrame`](/slides/python-net/hi/aspose.slides/ipictureframe).

```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype) में सम्मिलित shape प्रकार निर्दिष्ट करता है,<br/><br/>            सभी प्रकार की रेखाओं को छोड़कर:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | चित्र फ्रेम का x-निर्देशांक, बिंदुओं में। |
| y | **float** | चित्र फ्रेम का y-निर्देशांक, बिंदुओं में। |
| width | **float** | चित्र फ्रेम की चौड़ाई, बिंदुओं में। |
| height | **float** | चित्र फ्रेम की ऊँचाई, बिंदुओं में। |
| image | [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage) को चित्र फ्रेम में प्रदर्शित करने के लिये। |

### संबंधित देखें
* क्लास [`IPictureFrame`](/slides/python-net/hi/aspose.slides/ipictureframe)
* क्लास [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage)
* क्लास [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)
* एन्यूमरेशन [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)