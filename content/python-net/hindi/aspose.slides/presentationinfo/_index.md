---
title: PresentationInfo class
second_title: Aspose.Slides for Python के लिए .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides/presentationinfo/
---
## PresentationInfo क्लास

प्रेजेंटेशन फ़ाइल के बारे में जानकारी

PresentationInfo प्रकार निम्नलिखित सदस्यों को प्रकट करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`is_encrypted`](/slides/python-net/hi/aspose.slides/presentationinfo/is_encrypted/) | यदि बाइंडेड प्रेजेंटेशन एन्क्रिप्टेड है तो True लौटाता है, अन्यथा False.<br/>            केवल पढ़ने योग्य **bool**। |
| [`is_password_protected`](/slides/python-net/hi/aspose.slides/presentationinfo/is_password_protected/) | एक मान लौटाता है जो बताता है कि बाइंडेड प्रेजेंटेशन को खोलने के लिए पासवर्ड द्वारा सुरक्षित है या नहीं। |
| [`is_write_protected`](/slides/python-net/hi/aspose.slides/presentationinfo/is_write_protected/) | एक मान लौटाता है जो बताता है कि बाइंडेड प्रेजेंटेशन लिखने से सुरक्षित है या नहीं। |
| [`load_format`](/slides/python-net/hi/aspose.slides/presentationinfo/load_format/) | बाइंडेड प्रेजेंटेशन का फॉर्मेट प्राप्त करता है।<br/>            केवल पढ़ने योग्य [`LoadFormat`](/slides/python-net/hi/aspose.slides/loadformat)। |

## विधियाँ

| मेथड | विवरण |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/hi/aspose.slides/presentationinfo/write_binded_presentation/#iorawiobase) | बाइंडेड प्रेजेंटेशन को स्ट्रीम में लिखता है। |
| [`write_binded_presentation(self, file)`](/slides/python-net/hi/aspose.slides/presentationinfo/write_binded_presentation/#str) | बाइंडेड प्रेजेंटेशन को फ़ाइल में लिखता है। |
| [`check_password(self, password)`](/slides/python-net/hi/aspose.slides/presentationinfo/check_password/#str) | जाँचता है कि खुलने वाले पासवर्ड से सुरक्षित प्रेजेंटेशन के लिए पासवर्ड सही है या नहीं। |
| [`check_write_protection(self, password)`](/slides/python-net/hi/aspose.slides/presentationinfo/check_write_protection/#str) | जाँचता है कि संशोधन के लिए पासवर्ड लिखने-से-सुरक्षित प्रेजेंटेशन के लिए सही है या नहीं। |
| [`read_document_properties(self)`](/slides/python-net/hi/aspose.slides/presentationinfo/read_document_properties/#) | बाइंडेड प्रेजेंटेशन के दस्तावेज़ गुणों को प्राप्त करता है। |
| [`update_document_properties(self, document_properties)`](/slides/python-net/hi/aspose.slides/presentationinfo/update_document_properties/#idocumentproperties) | बाइंडेड प्रेजेंटेशन के गुणों को अद्यतन करता है। |


### देखें भी
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)