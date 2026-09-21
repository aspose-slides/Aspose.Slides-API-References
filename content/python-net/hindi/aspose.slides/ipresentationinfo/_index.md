---
title: IPresentationInfo class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ipresentationinfo/
---
## IPresentationInfo क्लास

प्रेजेंटेशन फ़ाइल के बारे में जानकारी

IPresentationInfo प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`is_encrypted`](/slides/python-net/hi/aspose.slides/ipresentationinfo/is_encrypted/) | यदि बाइंडेड प्रेजेंटेशन एन्क्रिप्टेड है तो True प्राप्त करता है, अन्यथा False.<br/>            केवल पढ़ने योग्य **bool**. |
| [`is_password_protected`](/slides/python-net/hi/aspose.slides/ipresentationinfo/is_password_protected/) | एक मान प्राप्त करता है जो यह दर्शाता है कि बाइंडेड प्रेजेंटेशन को खोलने के लिए पासवर्ड से संरक्षित है या नहीं. |
| [`is_write_protected`](/slides/python-net/hi/aspose.slides/ipresentationinfo/is_write_protected/) | एक मान प्राप्त करता है जो यह दर्शाता है कि बाइंडेड प्रेजेंटेशन लेखन-रक्षित है या नहीं. |
| [`load_format`](/slides/python-net/hi/aspose.slides/ipresentationinfo/load_format/) | बाइंडेड प्रेजेंटेशन का स्वरूप प्राप्त करता है.<br/>            केवल पढ़ने योग्य [`LoadFormat`](/slides/python-net/hi/aspose.slides/loadformat). |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/hi/aspose.slides/ipresentationinfo/write_binded_presentation/#iorawiobase) | बाइंडेड प्रेजेंटेशन को स्ट्रीम में लिखता है. |
| [`write_binded_presentation(self, file)`](/slides/python-net/hi/aspose.slides/ipresentationinfo/write_binded_presentation/#str) | बाइंडेड प्रेजेंटेशन को फ़ाइल में लिखता है. |
| [`check_password(self, password)`](/slides/python-net/hi/aspose.slides/ipresentationinfo/check_password/#str) | जांचता है कि खुला पासवर्ड द्वारा संरक्षित प्रेजेंटेशन के लिए पासवर्ड सही है या नहीं. |
| [`check_write_protection(self, password)`](/slides/python-net/hi/aspose.slides/ipresentationinfo/check_write_protection/#str) | जांचता है कि लेखन-रक्षित प्रेजेंटेशन के लिए संशोधित करने का पासवर्ड सही है या नहीं. |
| [`read_document_properties(self)`](/slides/python-net/hi/aspose.slides/ipresentationinfo/read_document_properties/#) | बाइंडेड प्रेजेंटेशन की दस्तावेज़ गुण प्राप्त करता है. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/hi/aspose.slides/ipresentationinfo/update_document_properties/#idocumentproperties) | बाइंडेड प्रेजेंटेशन के गुणों को अपडेट करता है. |

### संबंधित देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)