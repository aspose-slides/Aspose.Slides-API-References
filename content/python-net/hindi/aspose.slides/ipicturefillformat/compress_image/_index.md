---
title: compress_image method
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ipicturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
इमेज को आकार घटाकर, आकार के आकार और निर्दिष्ट रेजोल्यूशन के आधार पर कॉम्प्रेस करता है। वैकल्पिक रूप से, यह क्रॉप किए गए क्षेत्रों को भी हटा देता है।

### रिटर्न

एक **bool** जो दर्शाता है कि इमेज सफलतापूर्वक कॉम्प्रेस हुई या नहीं। यदि इमेज का आकार बदला गया या क्रॉप किया गया तो **True** लौटाता है, अन्यथा **False**।

```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| परामीटर | प्रकार | विवरण |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | यदि true हो, तो विधि इमेज के क्रॉप किए गए क्षेत्रों को हटा देगा, जिससे संभवतः आकार और घटाया जा सकता है। |
| resolution | [`PicturesCompression`](/slides/python-net/hi/aspose.slides.export/picturescompression) | कॉम्प्रेशन के लिए लक्ष्य रेजोल्यूशन, जिसे [`PicturesCompression`](/slides/python-net/hi/aspose.slides.export/picturescompression) एन्नम के मान के रूप में निर्दिष्ट किया गया है। |

### टिप्पणी

यह विधि इमेज के आकार और रेजोल्यूशन को PowerPoint के "Picture Format -> Compress Pictures" सुविधा के समान बदलती है।

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | जब रेजोल्यूशन मान्य नहीं हो तो थ्रो किया जाता है। |

## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
इमेज को आकार घटाकर, आकार के आकार और निर्दिष्ट रेजोल्यूशन के आधार पर कॉम्प्रेस करता है। वैकल्पिक रूप से, यह क्रॉप किए गए क्षेत्रों को भी हटा देता है।

### रिटर्न

एक **bool** जो दर्शाता है कि इमेज सफलतापूर्वक कॉम्प्रेस हुई या नहीं। यदि इमेज का आकार बदला गया या क्रॉप किया गया तो **True** लौटाता है, अन्यथा **False**।

```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| परामीटर | प्रकार | विवरण |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | यदि true हो, तो विधि इमेज के क्रॉप किए गए क्षेत्रों को हटा देगा, जिससे संभवतः आकार और घटाया जा सकता है। |
| resolution | **float** | DPI में लक्ष्य रेजोल्यूशन। यह मान सकारात्मक होना चाहिए और इमेज के पुनःआकार को निर्धारित करता है। |

### टिप्पणी

यह विधि इमेज के आकार और रेजोल्यूशन को PowerPoint के "Picture Format -> Compress Pictures" सुविधा के समान बदलती है।

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | जब रेजोल्यूशन सकारात्मक मान न हो तो थ्रो किया जाता है। |

### देखें
* क्लास [`IPictureFillFormat`](/slides/python-net/hi/aspose.slides/ipicturefillformat)
* एन्यूमरेशन [`PicturesCompression`](/slides/python-net/hi/aspose.slides.export/picturescompression)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)