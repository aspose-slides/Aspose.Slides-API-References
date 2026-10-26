---
title: add_group_shape method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ishapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
एक नया खाली समूह आकार बनाता है और उसे आकार संग्रह के अंत में जोड़ता है।
समूह का फ़्रेम स्वचालित रूप से जोड़े गए किसी भी आकार को फिट करने के लिए समायोजित हो जाएगा।

### Returns

नया बनाया गया [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape)।

```python
def add_group_shape(self):
    ...
```

## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
एक नया समूह आकार बनाता है, निर्दिष्ट SVG छवि को व्यक्तिगत आकार में परिवर्तित करता है,
और परिणामी समूह को आकार संग्रह के अंत में जोड़ता है।

### Returns

नया बनाया गया [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape)।

```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/hi/aspose.slides/isvgimage) | वह [`ISvgImage`](/slides/python-net/hi/aspose.slides/isvgimage) जिसमें वेक्टर सामग्री है जिसे आकारों में परिवर्तित किया जाएगा। |
| x | **float** | समूह के फ़्रेम का x-निर्धारक, बिंदुओं में। |
| y | **float** | समूह के फ़्रेम का y-निर्धारक, बिंदुओं में। |
| width | **float** | समूह के फ़्रेम की चौड़ाई, बिंदुओं में। |
| height | **float** | समूह के फ़्रेम की ऊँचाई, बिंदुओं में। |

### देखें भी
* क्लास [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape)
* क्लास [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)
* क्लास [`ISvgImage`](/slides/python-net/hi/aspose.slides/isvgimage)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)