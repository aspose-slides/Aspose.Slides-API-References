---
title: IStreamWrapper class
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/istreamwrapper/
---
## IStreamWrapper क्लास

Aspose.IO.Stream रैपर COM इंटरफ़ेस के लिए।

IStreamWrapper प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| संपत्ति | विवरण |
| :- | :- |
| [`stream`](/slides/python-net/hi/aspose.slides/istreamwrapper/stream/) | एक स्ट्रीम प्राप्त करता है।<br/>            केवल-पढ़ने योग्य **io.RawIOBase**. |
| [`can_read`](/slides/python-net/hi/aspose.slides/istreamwrapper/can_read/) | एक मान प्राप्त करता है जो दर्शाता है कि वर्तमान स्ट्रीम पढ़ने का समर्थन करता है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**. |
| [`can_seek`](/slides/python-net/hi/aspose.slides/istreamwrapper/can_seek/) | एक मान प्राप्त करता है जो दर्शाता है कि वर्तमान स्ट्रीम सीकिंग का समर्थन करता है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**. |
| [`can_write`](/slides/python-net/hi/aspose.slides/istreamwrapper/can_write/) | एक मान प्राप्त करता है जो दर्शाता है कि वर्तमान स्ट्रीम लिखने का समर्थन करता है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**. |
| [`length`](/slides/python-net/hi/aspose.slides/istreamwrapper/length/) | स्ट्रीम की लंबाई बाइट्स में प्राप्त करता है।<br/>            केवल-पढ़ने योग्य **int**. |
| [`position`](/slides/python-net/hi/aspose.slides/istreamwrapper/position/) | वर्तमान स्ट्रीम के भीतर स्थिति प्राप्त करता है।<br/>            केवल-पढ़ने योग्य **int**. |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`close(self)`](/slides/python-net/hi/aspose.slides/istreamwrapper/close/#) | वर्तमान स्ट्रीम को बंद करता है और सभी संसाधनों को रिलीज़ करता है। |
| [`flush(self)`](/slides/python-net/hi/aspose.slides/istreamwrapper/flush/#) | इस स्ट्रीम के सभी बफ़र साफ़ करता है और किसी भी बफ़र किए गए डेटा को मूल उपकरण पर लिखने का कारण बनाता है। |
| [`read(self, buffer, offset, count)`](/slides/python-net/hi/aspose.slides/istreamwrapper/read/#bytes-int-int) | वर्तमान स्ट्रीम से बाइट्स का क्रम पढ़ता है और पढ़े गए बाइट्स की संख्या से स्ट्रीम में स्थिति को आगे बढ़ाता है। |
| [`read_byte(self)`](/slides/python-net/hi/aspose.slides/istreamwrapper/read_byte/#) | स्ट्रीम से एक बाइट पढ़ता है और स्ट्रीम में स्थिति को एक बाइट से आगे बढ़ाता है, या यदि स्ट्रीम के अंत पर है तो -1 लौटाता है। |
| [`seek(self, offset, origin)`](/slides/python-net/hi/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | वर्तमान स्ट्रीम के भीतर स्थिति सेट करता है |
| [`write(self, buffer, offset, count)`](/slides/python-net/hi/aspose.slides/istreamwrapper/write/#bytes-int-int) | वर्तमान स्ट्रीम में बाइट्स का क्रम लिखता है और लिखे गए बाइट्स की संख्या से इस स्ट्रीम में वर्तमान स्थिति को आगे बढ़ाता है। |
| [`write_byte(self, value)`](/slides/python-net/hi/aspose.slides/istreamwrapper/write_byte/#int) | स्ट्रीम में वर्तमान स्थिति पर एक बाइट लिखता है और स्ट्रीम में स्थिति को एक बाइट से आगे बढ़ाता है। |

### देखें भी
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)