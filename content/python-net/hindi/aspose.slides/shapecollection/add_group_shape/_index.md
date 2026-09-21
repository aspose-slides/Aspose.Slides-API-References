---
title: add_group_shape method
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/shapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
एक नया खाली समूह आकार बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।
समूह का फ्रेम स्वचालित रूप से समायोजित हो जाएगा ताकि उसमें जोड़ी गई किसी भी आकृति को फिट कर सके।

### रिटर्न
नया निर्मित [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape)।

```python
def add_group_shape(self):
    ...
```

## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
एक नया समूह आकार बनाता है, निर्दिष्ट SVG छवि को अलग-अलग आकारों में बदलता है, और परिणामस्वरूप समूह को आकार संग्रह के अंत में जोड़ता है।
समूह का फ्रेम स्वचालित रूप से समायोजित हो जाएगा ताकि उसमें जोड़ी गई किसी भी आकृति को फिट कर सके।

### रिटर्न
नया निर्मित [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape)।

```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/hi/aspose.slides/isvgimage) | [`ISvgImage`](/slides/python-net/hi/aspose.slides/isvgimage) जिसमें वेक्टर सामग्री है जिसे आकारों में परिवर्तित किया जाएगा। |
| x | **float** | समूह के फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | समूह के फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | समूह के फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | समूह के फ्रेम की ऊँचाई, पॉइंट्स में। |

### देखें
* क्लास [`IGroupShape`](/slides/python-net/hi/aspose.slides/igroupshape)
* क्लास [`ISvgImage`](/slides/python-net/hi/aspose.slides/isvgimage)
* क्लास [`ShapeCollection`](/slides/python-net/hi/aspose.slides/shapecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)