---
title: insert_picture_frame method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/shapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
निर्दिष्ट छवि युक्त एक नया चित्र फ्रेम बनाता है और इसे निर्दिष्ट क्रमांक पर shape संग्रह में सम्मिलित करता है।

### रिटर्न
नया बनाया गया [`IPictureFrame`](/slides/python-net/hi/aspose.slides/ipictureframe)।

```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | वह शून्य-आधारित अनुक्रमांक जहाँ चित्र फ्रेम डालना है। |
| shape_type | [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype) में शामिल shape प्रकार को निर्दिष्ट करता है,<br/><br/>            सभी प्रकार की लाइनों को छोड़कर:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | चित्र फ्रेम का x-निर्देशांक, पॉइंट में। |
| y | **float** | चित्र फ्रेम का y-निर्देशांक, पॉइंट में। |
| width | **float** | चित्र फ्रेम की चौड़ाई, पॉइंट में। |
| height | **float** | चित्र फ्रेम की ऊँचाई, पॉइंट में। |
| image | [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage) | चित्र फ्रेम में दिखाने के लिए [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage)। |

### देखें
* क्लास [`IPictureFrame`](/slides/python-net/hi/aspose.slides/ipictureframe)
* क्लास [`IPPImage`](/slides/python-net/hi/aspose.slides/ippimage)
* क्लास [`ShapeCollection`](/slides/python-net/hi/aspose.slides/shapecollection)
* एन्युमरेशन [`ShapeType`](/slides/python-net/hi/aspose.slides/shapetype)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)