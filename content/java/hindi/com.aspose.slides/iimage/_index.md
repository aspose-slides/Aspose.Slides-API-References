---
title: IImage
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक रास्टर या वेक्टर छवि का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iimage/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

रास्टर या वेक्टर छवि को दर्शाता है।

--------------------

यह इंटरफ़ेस रास्टर और वेक्टर दोनों छवियों को संभालने के लिए एक सामान्य अभिकल्पना प्रदान करता है। कार्यान्वयन आधारभूत छवि प्रकार पर निर्भर करके भिन्न हो सकते हैं।
## Methods

| विधि | विवरण |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | छवि को फ़ाइल में सहेजता है। |
| [save(String filename, int format)](#save-java.lang.String-int-) | छवि को निर्दिष्ट स्वरूप में फ़ाइल में सहेजता है। |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | छवि को निर्दिष्ट स्वरूप में स्ट्रीम में सहेजता है। |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | छवि को निर्दिष्ट स्वरूप और गुणवत्ता में फ़ाइल में सहेजता है। |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | छवि को निर्दिष्ट स्वरूप और गुणवत्ता में स्ट्रीम में सहेजता है। |
| [getSize()](#getSize--) | छवि का आकार प्राप्त करता है। |
| [getWidth()](#getWidth--) | छवि की चौड़ाई पिक्सेल में प्राप्त करता है। |
| [getHeight()](#getHeight--) | छवि की ऊँचाई पिक्सेल में प्राप्त करता है। |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

छवि को फ़ाइल में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | java.lang.String | फ़ाइल का पथ जहाँ छवि सहेजी जाएगी। |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

छवि को निर्दिष्ट स्वरूप में फ़ाइल में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | java.lang.String | फ़ाइल का पथ जहाँ छवि सहेजी जाएगी। |
| format | int | छवि का स्वरूप। |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

छवि को निर्दिष्ट स्वरूप में स्ट्रीम में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | स्ट्रीम जहाँ छवि सहेजी जाएगी। |
| format | int | छवि का स्वरूप। |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

छवि को निर्दिष्ट स्वरूप और गुणवत्ता में फ़ाइल में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | java.lang.String | फ़ाइल का पथ जहाँ छवि सहेजी जाएगी। |
| format | int | छवि का स्वरूप। |
| quality | int | सहेजी गई छवि की गुणवत्ता (0 से 100)। यह पैरामीटर केवल [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) में सहेजने को प्रभावित करता है; अन्य सभी स्वरूपों के लिए यह अनदेखा किया जाता है। |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

छवि को निर्दिष्ट स्वरूप और गुणवत्ता में स्ट्रीम में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | स्ट्रीम जहाँ छवि सहेजी जाएगी। |
| format | int | छवि का स्वरूप। |
| quality | int | सहेजी गई छवि की गुणवत्ता (0 से 100)। यह पैरामीटर केवल [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) में सहेजने को प्रभावित करता है; अन्य सभी स्वरूपों के लिए यह अनदेखा किया जाता है। |

### getSize() {#getSize--}
```
public abstract Dimension getSize()
```

छवि का आकार प्राप्त करता है।

**रिटर्न:**
java.awt.Dimension
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

छवि की चौड़ाई पिक्सेल में प्राप्त करता है।

**रिटर्न:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

छवि की ऊँचाई पिक्सेल में प्राप्त करता है।

**रिटर्न:**
int