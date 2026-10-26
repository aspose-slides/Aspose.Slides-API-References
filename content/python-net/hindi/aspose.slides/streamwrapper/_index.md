---
title: StreamWrapper class
second_title: Aspose.Slides के लिए Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/streamwrapper/
---
## StreamWrapper क्लास

Aspose.IO.Stream रैपर COM इंटरफ़ेस के लिए।

The StreamWrapper type निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| गुण | विवरण |
| :- | :- |
| [`stream`](/slides/python-net/hi/aspose.slides/streamwrapper/stream/) | एक स्ट्रीम प्राप्त करता है।<br/>            केवल-पढ़ने योग्य **io.RawIOBase**। |
| [`can_read`](/slides/python-net/hi/aspose.slides/streamwrapper/can_read/) | एक मान प्राप्त करता है जो दर्शाता है कि वर्तमान स्ट्रीम पढ़ने का समर्थन करता है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**। |
| [`can_seek`](/slides/python-net/hi/aspose.slides/streamwrapper/can_seek/) | एक मान प्राप्त करता है जो दर्शाता है कि वर्तमान स्ट्रीम सीकिंग का समर्थन करता है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**। |
| [`can_write`](/slides/python-net/hi/aspose.slides/streamwrapper/can_write/) | एक मान प्राप्त करता है जो दर्शाता है कि वर्तमान स्ट्रीम लिखने का समर्थन करता है या नहीं।<br/>            केवल-पढ़ने योग्य **bool**। |
| [`length`](/slides/python-net/hi/aspose.slides/streamwrapper/length/) | स्ट्रीम की लंबाई बाइट्स में प्राप्त करता है।<br/>            केवल-पढ़ने योग्य **int**। |
| [`position`](/slides/python-net/hi/aspose.slides/streamwrapper/position/) | वर्तमान स्ट्रीम के भीतर स्थिति प्राप्त करता या सेट करता है।<br/>            केवल-पढ़ने योग्य **int**। |

## विधियाँ

| विधि | विवरण |
| :- | :- |
| [`close(self)`](/slides/python-net/hi/aspose.slides/streamwrapper/close/#) | वर्तमान स्ट्रीम को बंद करता है और सभी संसाधनों को रिलीज़ करता है। |
| [`flush(self)`](/slides/python-net/hi/aspose.slides/streamwrapper/flush/#) | इस स्ट्रीम के सभी बफ़र को साफ़ करता है और बफ़र किए गए डेटा को आधारभूत उपकरण पर लिखवाता है। |
| [`read(self, buffer, offset, count)`](/slides/python-net/hi/aspose.slides/streamwrapper/read/#bytes-int-int) | वर्तमान स्ट्रीम से बाइट्स की एक श्रृंखला पढ़ता है और पढ़े गए बाइट्स की संख्या से स्ट्रीम में स्थिति को आगे बढ़ाता है। |
| [`read_byte(self)`](/slides/python-net/hi/aspose.slides/streamwrapper/read_byte/#) | स्ट्रीम से एक बाइट पढ़ता है और स्ट्रीम में स्थिति को एक बाइट आगे बढ़ाता है, या यदि स्ट्रीम के अंत में हो तो -1 लौटाता है। |
| [`seek(self, offset, origin)`](/slides/python-net/hi/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | वर्तमान स्ट्रीम के भीतर स्थिति को सेट करता है। |
| [`write(self, buffer, offset, count)`](/slides/python-net/hi/aspose.slides/streamwrapper/write/#bytes-int-int) | वर्तमान स्ट्रीम में बाइट्स की एक श्रृंखला लिखता है और लिखे गए बाइट्स की संख्या से इस स्ट्रीम में वर्तमान स्थिति को आगे बढ़ाता है। |
| [`write_byte(self, value)`](/slides/python-net/hi/aspose.slides/streamwrapper/write_byte/#int) | स्ट्रीम में वर्तमान स्थिति पर एक बाइट लिखता है और स्ट्रीम में स्थिति को एक बाइट आगे बढ़ाता है। |

### देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)