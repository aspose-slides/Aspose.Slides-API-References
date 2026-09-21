---
title: compress_image method
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/picturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
छवि को उसके आकार को आकार और निर्दिष्ट रिज़ॉल्यूशन के आधार पर घटाकर संकुचित करता है। वैकल्पिक रूप से, यह क्रॉप किए गए क्षेत्रों को भी हटा देता है।

### वापसी

एक **bool** जो दर्शाता है कि छवि सफलतापूर्वक संकुचित की गई थी या नहीं। यदि छवि का आकार बदल दिया गया या क्रॉप किया गया, तो **True** लौटाता है, अन्यथा **False**।

```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | यदि true हो, तो मेथड छवि के कटे हुए हिस्सों को हटा देगा, जिससे उसका आकार और भी कम हो सकता है। |
| resolution | [`PicturesCompression`](/slides/python-net/hi/aspose.slides.export/picturescompression) | संकुचन के लिए लक्ष्य रिज़ॉल्यूशन, जो [`PicturesCompression`](/slides/python-net/hi/aspose.slides.export/picturescompression) enum के मान के रूप में निर्दिष्ट है। |

### टिप्पणी

यह मेथड छवि का आकार और रिज़ॉल्यूशन बदलता है, जैसे PowerPoint के “Picture Format -> Compress Pictures” फीचर में होता है।

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | जब रिज़ॉल्यूशन वैध मान नहीं होता है, तब फेंका जाता है। |

## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
छवि को उसके आकार को आकार और निर्दिष्ट रिज़ॉल्यूशन के आधार पर घटाकर संकुचित करता है। वैकल्पिक रूप से, यह क्रॉप किए गए क्षेत्रों को भी हटा देता है।

### वापसी

एक **bool** जो दर्शाता है कि छवि सफलतापूर्वक संकुचित की गई थी या नहीं। यदि छवि का आकार बदल दिया गया या क्रॉप किया गया, तो **True** लौटाता है, अन्यथा **False**।

```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | यदि true हो, तो मेथड छवि के कटे हुए हिस्सों को हटा देगा, जिससे उसका आकार और भी कम हो सकता है। |
| resolution | **float** | लक्षित रिज़ॉल्यूशन DPI में। यह मान सकारात्मक होना चाहिए और यह निर्धारित करता है कि छवि का आकार कैसे बदलेगा। |

### टिप्पणी

यह मेथड छवि का आकार और रिज़ॉल्यूशन बदलता है, जैसे PowerPoint के “Picture Format -> Compress Pictures” फीचर में होता है।

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | जब रिज़ॉल्यूशन सकारात्मक मान नहीं होता है, तब फेंका जाता है। |

### देखें
* क्लास [`PictureFillFormat`](/slides/python-net/hi/aspose.slides/picturefillformat)
* एन्यूमरेशन [`PicturesCompression`](/slides/python-net/hi/aspose.slides.export/picturescompression)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)