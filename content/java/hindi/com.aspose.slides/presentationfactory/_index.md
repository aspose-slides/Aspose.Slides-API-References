---
title: PresentationFactory
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: COM इंटरफ़ेस के माध्यम से प्रस्तुति बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/presentationfactory/
---
**विरासत:**
java.lang.Object

**सभी लागू किए गए इंटरफ़ेस:**
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
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getInstance()](#getInstance--) | प्रेज़ेंटेशन फ़ैक्ट्री स्थिर इंस्टेंस। |
| [createPresentation()](#createPresentation--) | नई प्रस्तुति बनाता है। |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | अतिरिक्त लोड विकल्पों के साथ नई प्रस्तुति बनाता है |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | फ़ाइल से नया PresentationInfo ऑब्जेक्ट बनाता है और प्रस्तुति को उससे बाइंड करता है। |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | स्ट्रीम से नया PresentationInfo ऑब्जेक्ट बनाता है और प्रस्तुति को उससे बाइंड करता है। |
| [readPresentation(byte[] data)](#readPresentation-byte---) | ऐर्रे से मौजूदा प्रस्तुति पढ़ता है |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | ऐर्रे से मौजूदा प्रस्तुति को अतिरिक्त लोड विकल्पों के साथ पढ़ता है |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | स्ट्रीम से मौजूदा प्रस्तुति पढ़ता है |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | स्ट्रीम से मौजूदा प्रस्तुति को अतिरिक्त लोड विकल्पों के साथ पढ़ता है |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | फ़ाइल से मौजूदा प्रस्तुति पढ़ता है |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | स्ट्रीम से मौजूदा प्रस्तुति को अतिरिक्त लोड विकल्पों के साथ पढ़ता है |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | स्लाइड्स से कच्चा पाठ प्राप्त करता है |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | स्लाइड्स से कच्चा पाठ प्राप्त करता है |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | स्लाइड्स से कच्चा पाठ प्राप्त करता है |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```


### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```


प्रेज़ेंटेशन फ़ैक्ट्री स्थिर इंस्टेंस। केवल पढ़ने योग्य [PresentationFactory](../../com.aspose.slides/presentationfactory).

**वापसी:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```


नई प्रस्तुति बनाता है।

**वापसी:**
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

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation) - नई प्रस्तुति
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```


फ़ाइल से नया PresentationInfo ऑब्जेक्ट बनाता है और प्रस्तुति को उससे बाइंड करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | java.lang.String | प्रेज़ेंटेशन फ़ाइल। |

**वापसी:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - प्रस्तुति से बंधी हुई प्रेज़ेंटेशन जानकारी।
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```


स्ट्रीम से नया PresentationInfo ऑब्जेक्ट बनाता है और प्रस्तुति को उससे बाइंड करता है। निर्दिष्ट स्ट्रीम में प्रस्तुति की जानकारी प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | प्रेज़ेंटेशन स्ट्रीम। |

**वापसी:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - प्रस्तुति से बंधी हुई प्रेज़ेंटेशन जानकारी।
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```


ऐर्रे से मौजूदा प्रस्तुति पढ़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | byte[] | पढ़ने के लिए ऐर्रे |

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation) - पढ़ी गई प्रस्तुति
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```


ऐर्रे से मौजूदा प्रस्तुति को अतिरिक्त लोड विकल्पों के साथ पढ़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | byte[] | पढ़ने के लिए ऐर्रे |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | लोड विकल्प |

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation) - पढ़ी गई प्रस्तुति
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```


स्ट्रीम से मौजूदा प्रस्तुति पढ़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | पढ़ने के लिए इनपुट स्ट्रीम |

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation) - पढ़ी गई प्रस्तुति
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```


स्ट्रीम से मौजूदा प्रस्तुति को अतिरिक्त लोड विकल्पों के साथ पढ़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | पढ़ने के लिए इनपुट स्ट्रीम |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | लोड विकल्प |

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation) - पढ़ी गई प्रस्तुति
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
```


फ़ाइल से मौजूदा प्रस्तुति पढ़ता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | java.lang.String | फ़ाइल नाम |

**वापसी:**
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

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation) - पढ़ी गई प्रस्तुति
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```


स्लाइड्स से कच्चा पाठ प्राप्त करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | java.lang.String | इनपुट फ़ाइल |
| mode | int | निकालने का मोड |

**वापसी:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - PresentationText का वह इंस्टेंस जिसमें SlideText ऐरे है जो कच्चा स्लाइड टेक्स्ट दर्शाता है
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```


स्लाइड्स से कच्चा पाठ प्राप्त करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | इनपुट स्ट्रीम |
| mode | int | निकालने का मोड |

**वापसी:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - PresentationText का वह इंस्टेंस जिसमें SlideText ऐरे है जो कच्चा स्लाइड टेक्स्ट दर्शाता है
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```


स्लाइड्स से कच्चा पाठ प्राप्त करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | इनपुट स्ट्रीम |
| mode | int | निकालने का मोड |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | लोड विकल्प |

**वापसी:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - PresentationText का वह इंस्टेंस जिसमें SlideText ऐरे है जो कच्चा स्लाइड टेक्स्ट दर्शाता है