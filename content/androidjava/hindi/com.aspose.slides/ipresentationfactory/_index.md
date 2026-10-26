---
title: IPresentationFactory
second_title: Aspose.Slides for Android via Java API Reference
description: COM इंटरफ़ेस के माध्यम से प्रस्तुति बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

COM इंटरफ़ेस के माध्यम से प्रस्तुति बनाने की अनुमति देता है

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [createPresentation()](#createPresentation--) | नई प्रस्तुति बनाता है। |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | अतिरिक्त लोड विकल्पों के साथ नई प्रस्तुति बनाता है। |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | निर्दिष्ट फ़ाइल में प्रस्तुति की जानकारी प्राप्त करता है। |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | निर्दिष्ट स्ट्रीम में प्रस्तुति की जानकारी प्राप्त करता है। |
| [readPresentation(byte[] data)](#readPresentation-byte---) | ऐरे से मौजूदा प्रस्तुति पढ़ता है। |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | अतिरिक्त लोड विकल्पों के साथ ऐरे से मौजूदा प्रस्तुति पढ़ता है। |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | स्ट्रीम से मौजूदा प्रस्तुति पढ़ता है। |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | अतिरिक्त लोड विकल्पों के साथ स्ट्रीम से मौजूदा प्रस्तुति पढ़ता है। |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | फ़ाइल से मौजूदा प्रस्तुति पढ़ता है। |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | अतिरिक्त लोड विकल्पों के साथ स्ट्रीम से मौजूदा प्रस्तुति पढ़ता है। |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | स्लाइड से कच्चा टेक्स्ट प्राप्त करता है। |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | स्लाइड से कच्चा टेक्स्ट प्राप्त करता है। |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | स्लाइड से कच्चा टेक्स्ट प्राप्त करता है। |

### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```

नई प्रस्तुति बनाता है।

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation) - नई प्रस्तुति

### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
```

अतिरिक्त लोड विकल्पों के साथ नई प्रस्तुति बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | लोड विकल्प |

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation) - नई प्रस्तुति

### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public abstract IPresentationInfo getPresentationInfo(String file)
```

निर्दिष्ट फ़ाइल में प्रस्तुति की जानकारी प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | java.lang.String | प्रस्तुति फ़ाइल। |

**रिटर्न:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - प्रस्तुति जानकारी

### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```

निर्दिष्ट स्ट्रीम में प्रस्तुति की जानकारी प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | प्रस्तुति स्ट्रीम। |

**रिटर्न:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - प्रस्तुति जानकारी।

### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```

ऐरे से मौजूदा प्रस्तुति पढ़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | byte[] | पढ़ने के लिए ऐरे |

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation) - पढ़ी गई प्रस्तुति

### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```

अतिरिक्त लोड विकल्पों के साथ ऐरे से मौजूदा प्रस्तुति पढ़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | byte[] | पढ़ने के लिए ऐरे |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | लोड विकल्प |

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation) - पढ़ी गई प्रस्तुति

### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```

स्ट्रीम से मौजूदा प्रस्तुति पढ़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | पढ़ने के लिए इनपुट स्ट्रीम |

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation) - पढ़ी गई प्रस्तुति

### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

अतिरिक्त लोड विकल्पों के साथ स्ट्रीम से मौजूदा प्रस्तुति पढ़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | पढ़ने के लिए इनपुट स्ट्रीम |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | लोड विकल्प |

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation) - पढ़ी गई प्रस्तुति

### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```

फ़ाइल से मौजूदा प्रस्तुति पढ़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | java.lang.String | फ़ाइल नाम |

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation) - पढ़ी गई प्रस्तुति

### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```

अतिरिक्त लोड विकल्पों के साथ फ़ाइल से मौजूदा प्रस्तुति पढ़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | java.lang.String | फ़ाइल नाम |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | लोड विकल्प |

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation) - पढ़ी गई प्रस्तुति

### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```

स्लाइड से कच्चा टेक्स्ट प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | java.lang.String | इनपुट फ़ाइल |
| mode | int | निष्कर्षण मोड |

**रिटर्न:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - PresentationText का वह इंस्टेंस जिसमें SlideText ऐरे कच्चे स्लाइड टेक्स्ट को दर्शाता है

### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```

स्लाइड से कच्चा टेक्स्ट प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | इनपुट स्ट्रीम |
| mode | int | निष्कर्षण मोड |

**रिटर्न:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - PresentationText का वह इंस्टेंस जिसमें SlideText ऐरे कच्चे स्लाइड टेक्स्ट को दर्शाता है

### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

स्लाइड से कच्चा टेक्स्ट प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | इनपुट स्ट्रीम |
| mode | int | निष्कर्षण मोड |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | लोड विकल्प |

**रिटर्न:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - PresentationText का वह इंस्टेंस जिसमें SlideText ऐरे कच्चे स्लाइड टेक्स्ट को दर्शाता है