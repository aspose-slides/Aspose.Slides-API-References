---
title: PresentationFactory
second_title: Java API रेफ़रेंस के माध्यम से Android के लिए Aspose.Slides
description: COM इंटरफ़ेस के माध्यम से प्रस्तुति बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/presentationfactory/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)  
```
public class PresentationFactory implements IPresentationFactory
```

COM इंटरफ़ेस के माध्यम से प्रस्तुति बनाने की अनुमति देता है

--------------------

> ```
> The following example shows how to checking a Presentation Format.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  System.out.println(info.getLoadFormat()); // PPTX
>  IPresentationInfo info2 = PresentationFactory.getInstance().getPresentationInfo("pres.ppt");
>  System.out.println(info2.getLoadFormat()); // PPT
>  IPresentationInfo info3 = PresentationFactory.getInstance().getPresentationInfo("pres.odp");
>  System.out.println(info3.getLoadFormat()); // ODP
>  
>  The following example shows how to getting the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  System.out.println(props.getCreatedTime());
>  System.out.println(props.getSubject());
>  System.out.println(props.getTitle());
>  // ..
>  
>  The following example shows how to updating the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setTitle("My title");
>  info.updateDocumentProperties(props);
> ```

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getInstance()](#getInstance--) | Presentation स्थिर फ़ैक्टरी उदाहरण। |
| [createPresentation()](#createPresentation--) | नई प्रस्तुति बनाता है। |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | अतिरिक्त लोड विकल्पों के साथ नई प्रस्तुति बनाता है |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | फ़ाइल से नया PresentationInfo ऑब्जेक्ट बनाता है और प्रस्तुति को इससे बाइंड करता है। |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | स्ट्रीम से नया PresentationInfo ऑब्जेक्ट बनाता है और प्रस्तुति को इससे बाइंड करता है। |
| [readPresentation(byte[] data)](#readPresentation-byte---) | ऐरे से मौजूदा प्रस्तुति को पढ़ता है |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | ऐरे से मौजूदा प्रस्तुति को अतिरिक्त लोड विकल्पों के साथ पढ़ता है |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | स्ट्रीम से मौजूदा प्रस्तुति को पढ़ता है |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | स्ट्रीम से मौजूदा प्रस्तुति को अतिरिक्त लोड विकल्पों के साथ पढ़ता है |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | फ़ाइल से मौजूदा प्रस्तुति को पढ़ता है |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | स्ट्रीम से मौजूदा प्रस्तुति को अतिरिक्त लोड विकल्पों के साथ पढ़ता है |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | स्लाइडों से कच्चा पाठ प्राप्त करता है |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | स्लाइडों से कच्चा पाठ प्राप्त करता है |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | स्लाइडों से कच्चा पाठ प्राप्त करता है |

### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```

### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```

Presentation फ़ैक्टरी स्थिर उदाहरण। केवल-पढ़ने योग्य [PresentationFactory](../../com.aspose.slides/presentationfactory).

**रिटर्न:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)

### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```

नई प्रस्तुति बनाता है।

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation) - नई प्रस्तुति

### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```

अतिरिक्त लोड विकल्पों के साथ नई प्रस्तुति बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | लोड विकल्प |

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation) - नई प्रस्तुति

### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```

फ़ाइल से नया PresentationInfo ऑब्जेक्ट बनाता है और प्रस्तुति को इससे बाइंड करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | java.lang.String | प्रस्तुति फ़ाइल। |

**रिटर्न:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - प्रस्तुति जानकारी जो प्रस्तुति से बाइंड हुई है।

### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```

स्ट्रीम से नया PresentationInfo ऑब्जेक्ट बनाता है और प्रस्तुति को इससे बाइंड करता है। निर्दिष्ट स्ट्रीम में प्रस्तुति की जानकारी प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | प्रस्तुति स्ट्रीम। |

**रिटर्न:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - प्रस्तुति जानकारी जो प्रस्तुति से बाइंड हुई है।

### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```

ऐरे से मौजूदा प्रस्तुति को पढ़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | byte[] | पढ़ने के लिये ऐरे |

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation) - पढ़ी गई प्रस्तुति

### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```

ऐरे से मौजूदा प्रस्तुति को अतिरिक्त लोड विकल्पों के साथ पढ़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | byte[] | पढ़ने के लिये ऐरे |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | लोड विकल्प |

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation) - पढ़ी गई प्रस्तुति

### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```

स्ट्रीम से मौजूदा प्रस्तुति को पढ़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | पढ़ने के लिये इनपुट स्ट्रीम |

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation) - पढ़ी गई प्रस्तुति

### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

स्ट्रीम से मौजूदा प्रस्तुति को अतिरिक्त लोड विकल्पों के साथ पढ़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | पढ़ने के लिये इनपुट स्ट्रीम |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | लोड विकल्प |

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation) - पढ़ी गई प्रस्तुति

### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
```

फ़ाइल से मौजूदा प्रस्तुति को पढ़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | java.lang.String | फ़ाइल नाम |

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation) - पढ़ी गई प्रस्तुति

### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(String file, ILoadOptions options)
```

फ़ाइल से मौजूदा प्रस्तुति को अतिरिक्त लोड विकल्पों के साथ पढ़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | java.lang.String | फ़ाइल नाम |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | लोड विकल्प |

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation) - पढ़ी गई प्रस्तुति

### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```

स्लाइडों से कच्चा पाठ प्राप्त करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | java.lang.String | इनपुट फ़ाइल |
| mode | int | निकालने का मोड |

**रिटर्न:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - PresentationText का वह उदाहरण जिसमें SlideText ऐरे है जो कच्चा स्लाइड पाठ दर्शाता है

### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```

स्लाइडों से कच्चा पाठ प्राप्त करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | इनपुट स्ट्रीम |
| mode | int | निकालने का मोड |

**रिटर्न:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - PresentationText का वह उदाहरण जिसमें SlideText ऐरे है जो कच्चा स्लाइड पाठ दर्शाता है

### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

स्लाइडों से कच्चा पाठ प्राप्त करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | इनपुट स्ट्रीम |
| mode | int | निकालने का मोड |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | लोड विकल्प |

**रिटर्न:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - PresentationText का वह उदाहरण जिसमें SlideText ऐरे है जो कच्चा स्लाइड पाठ दर्शाता है