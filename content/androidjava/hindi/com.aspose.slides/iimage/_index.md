---
title: IImage
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: रास्टर या वेक्टर छवि का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iimage/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

छवि एक रास्टर या वेक्टर इमेज का प्रतिनिधित्व करती है।

--------------------

यह इंटरफ़ेस रास्टर और वेक्टर दोनों इमेज को संभालने के लिए एक सामान्य अमूर्तन प्रदान करता है। कार्यान्वयन अंतर्निहित इमेज प्रकार के आधार पर भिन्न हो सकते हैं।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | छवि को फ़ाइल में सहेजता है। |
| [save(String filename, int format)](#save-java.lang.String-int-) | छवि को निर्दिष्ट फ़ॉर्मेट में फ़ाइल में सहेजता है। |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | छवि को निर्दिष्ट फ़ॉर्मेट में स्ट्रीम में सहेजता है। |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | छवि को निर्दिष्ट फ़ॉर्मेट और गुणवत्ता में फ़ाइल में सहेजता है। |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | छवि को निर्दिष्ट फ़ॉर्मेट और गुणवत्ता में स्ट्रीम में सहेजता है। |
| [getSize()](#getSize--) | छवि का आकार प्राप्त करता है। |
| [getWidth()](#getWidth--) | छवि की चौड़ाई पिक्सल में प्राप्त करता है। |
| [getHeight()](#getHeight--) | छवि की ऊँचाई पिक्सल में प्राप्त करता है। |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

छवि को फ़ाइल में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | java.lang.String | फ़ाइल का वह पथ जहाँ छवि सहेजी जाएगी। |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

छवि को निर्दिष्ट फ़ॉर्मेट में फ़ाइल में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | java.lang.String | फ़ाइल का वह पथ जहाँ छवि सहेजी जाएगी। |
| format | int | छवि का फ़ॉर्मेट। |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

छवि को निर्दिष्ट फ़ॉर्मेट में स्ट्रीम में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | स्ट्रीम जहाँ छवि सहेजी जाएगी। |
| format | int | छवि का फ़ॉर्मेट। |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

छवि को निर्दिष्ट फ़ॉर्मेट और गुणवत्ता में फ़ाइल में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | java.lang.String | फ़ाइल का वह पथ जहाँ छवि सहेजी जाएगी। |
| format | int | छवि का फ़ॉर्मेट। |
| quality | int | सहेजी गई छवि की गुणवत्ता (0 से 100)। यह पैरामीटर केवल [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) में सहेजने को प्रभावित करता है; अन्य सभी फ़ॉर्मेट के लिए इसे नजरअंदाज़ किया जाता है। |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

छवि को निर्दिष्ट फ़ॉर्मेट और गुणवत्ता में स्ट्रीम में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | स्ट्रीम जहाँ छवि सहेजी जाएगी। |
| format | int | छवि का फ़ॉर्मेट। |
| quality | int | सहेजी गई छवि की गुणवत्ता (0 से 100)। यह पैरामीटर केवल [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) में सहेजने को प्रभावित करता है; अन्य सभी फ़ॉर्मेट के लिए इसे नजरअंदाज़ किया जाता है। |

### getSize() {#getSize--}
```
public abstract Size getSize()
```

छवि का आकार प्राप्त करता है।

**वापसी मान:**
[Size](../../com.aspose.slides.android/size)

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

छवि की चौड़ाई पिक्सल में प्राप्त करता है।

**वापसी मान:**
int

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

छवि की ऊँचाई पिक्सल में प्राप्त करता है।

**वापसी मान:**
int