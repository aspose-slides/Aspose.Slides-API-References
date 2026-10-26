---
title: PPImage class
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ppimage/
---
## PPImage वर्ग

एक प्रस्तुति में छवि का प्रतिनिधित्व करता है।

PPImage प्रकार निम्नलिखित सदस्यों को प्रकट करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`binary_data`](/slides/python-net/hi/aspose.slides/ppimage/binary_data/) | छवि के डेटा की प्रतिलिपि लौटाता है।<br/>            केवल-पढ़ने योग्य **int**[]. |
| [`image`](/slides/python-net/hi/aspose.slides/ppimage/image/) | छवि की प्रतिलिपि लौटाता है।<br/>            केवल-पढ़ने योग्य [`IImage`](/slides/python-net/hi/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/hi/aspose.slides/ppimage/svg_image/) | ISvgImage ऑब्जेक्ट [`ISvgImage`](/slides/python-net/hi/aspose.slides/isvgimage) को लौटाता है या सेट करता है |
| [`content_type`](/slides/python-net/hi/aspose.slides/ppimage/content_type/) | छवि का MIME प्रकार लौटाता है, जो [`PPImage.binary_data`](/slides/python-net/hi/aspose.slides/ppimage/binary_data) में एन्कोड किया गया है।<br/>            केवल-पढ़ने योग्य **str**. |
| [`width`](/slides/python-net/hi/aspose.slides/ppimage/width/) | छवि की चौड़ाई लौटाता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`height`](/slides/python-net/hi/aspose.slides/ppimage/height/) | छवि की ऊँचाई लौटाता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`x`](/slides/python-net/hi/aspose.slides/ppimage/x/) | छवि का X-ऑफ़सेट लौटाता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`y`](/slides/python-net/hi/aspose.slides/ppimage/y/) | छवि का Y-ऑफ़सेट लौटाता है।<br/>            केवल-पढ़ने योग्य **int**. |

## विधियां

| विधि | विवरण |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/hi/aspose.slides/ppimage/replace_image/#bytes) | छवि डेटा को बदलता है।<br/>            नया छवि डेटा। जब newImageData पैरामीटर None हो। |
| [`replace_image(self, new_image)`](/slides/python-net/hi/aspose.slides/ppimage/replace_image/#iimage) | छवि डेटा को बदलता है। ध्यान दें: जब Image मेटा-फ़ाइल है - इसे रास्टर किया जाएगा। ReplaceImage(byte[]) का उपयोग करें।<br/>            नई छवि। जब newImage पैरामीटर None हो। |
| [`replace_image(self, new_image)`](/slides/python-net/hi/aspose.slides/ppimage/replace_image/#ippimage) | छवि डेटा को बदलता है।<br/>            नया IPPImage। जब newImage पैरामीटर None हो। |


### संबंधित देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)