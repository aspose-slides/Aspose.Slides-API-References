---
title: IVideo class
second_title: Aspose.Slides Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ivideo/
---
## IVideo वर्ग

एक प्रस्तुतिकरण में एम्बेड किए गए वीडियो का प्रतिनिधित्व करता है।

IVideo प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुणधर्म

| गुण | विवरण |
| :- | :- |
| [`content_type`](/slides/python-net/hi/aspose.slides/ivideo/content_type/) | एक वीडियो का MIME प्रकार लौटाता है, जो [`IVideo.binary_data`](/slides/python-net/hi/aspose.slides/ivideo/binary_data) में एन्कोडेड है।<br/>            Read-only **str**. |
| [`binary_data`](/slides/python-net/hi/aspose.slides/ivideo/binary_data/) | ऑडियो डेटा की प्रति लौटाता है। बड़े डेटा की मात्रा के मामले में <br/>            [`IVideo.get_stream`](/slides/python-net/hi/aspose.slides/ivideo/get_stream) मेथड का उपयोग करने पर विचार करें ताकि वीडियो डेटा को मेमोरी में अनावश्यक रूप से लोड करने या यहाँ तक कि OutOfMemoryException से बचा जा सके।<br/>            Read-only **int**[]. |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/hi/aspose.slides/ivideo/get_stream/#) | पढ़ने के लिए Stream स्ट्रीम लौटाता है।<br/>            'using' का उपयोग करें या उपयोग के बाद स्ट्रीम को बंद करें। |


### संबंधित देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)