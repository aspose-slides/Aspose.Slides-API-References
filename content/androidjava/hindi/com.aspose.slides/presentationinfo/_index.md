---
title: PresentationInfo
second_title: Aspose.Slides Android के लिए Java API रेफरेंस
description: प्रस्तुति फ़ाइल के बारे में जानकारी
type: docs
url: /hi/com.aspose.slides/presentationinfo/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफेस:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

प्रस्तुति फ़ाइल के बारे में जानकारी
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | यदि बाइंडेड प्रस्तुति एन्क्रिप्टेड है तो True प्राप्त करता है, अन्यथा False। |
| [isPasswordProtected()](#isPasswordProtected--) | एक मान प्राप्त करता है जो दर्शाता है कि बाइंडेड प्रस्तुति को खोलने के लिए पासवर्ड से संरक्षित है या नहीं। |
| [isWriteProtected()](#isWriteProtected--) | एक मान प्राप्त करता है जो दर्शाता है कि बाइंडेड प्रस्तुति लिखने के लिए संरक्षित है या नहीं। |
| [getLoadFormat()](#getLoadFormat--) | बाइंडेड प्रस्तुति का फ़ॉर्मेट प्राप्त करता है। |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | जाँच करता है कि खुला पासवर्ड द्वारा संरक्षित प्रस्तुति के लिए पासवर्ड सही है या नहीं। |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | जाँच करता है कि लिखने योग्य संरक्षित प्रस्तुति के लिए संशोधन पासवर्ड सही है या नहीं। |
| [readDocumentProperties()](#readDocumentProperties--) | बाइंडेड प्रस्तुति की दस्तावेज़ गुण प्राप्त करता है। |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | बाइंडेड प्रस्तुति के गुण अपडेट करता है। |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | बाइंडेड प्रस्तुति को स्ट्रीम में लिखता है। |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | बाइंडेड प्रस्तुति को फ़ाइल में लिखता है। |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

यदि बाइंडेड प्रस्तुति एन्क्रिप्टेड है तो True प्राप्त करता है, अन्यथा False। केवल पढ़ने योग्य boolean.

**वापसी:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

एक मान प्राप्त करता है जो दर्शाता है कि बाइंडेड प्रस्तुति को खोलने के लिए पासवर्ड से संरक्षित है या नहीं।

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

**वापसी:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```

एक मान प्राप्त करता है जो दर्शाता है कि बाइंडेड प्रस्तुति लिखने के लिए संरक्षित है या नहीं।

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

यदि प्रस्तुति को खोलने के लिए पासवर्ड से संरक्षित किया गया है, तो प्रॉपर्टी मान NotDefined के बराबर होता है।

**वापसी:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

बाइंडेड प्रस्तुति का फ़ॉर्मेट प्राप्त करता है। केवल पढ़ने योग्य [LoadFormat](../../com.aspose.slides/loadformat)।

**वापसी:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

जाँच करता है कि खुला पासवर्ड द्वारा संरक्षित प्रस्तुति के लिए पासवर्ड सही है या नहीं।

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| password | java.lang.String | जाँच करने के लिए पासवर्ड। |

--------------------

जब पासवर्ड null या empty होता है, यह मेथड false लौटाता है. |

**वापसी:**
boolean - True यदि प्रस्तुति खुला पासवर्ड से संरक्षित है और पासवर्ड सही है, अन्यथा false।

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

जाँच करता है कि लिखने योग्य संरक्षित प्रस्तुति के लिए संशोधन पासवर्ड सही है या नहीं।

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```


**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| password | java.lang.String | जाँच करने के लिए पासवर्ड। |

--------------------

1. आपको इस मेथड को कॉल करने से पहले (\#isWriteProtected.isWriteProtected) प्रॉपर्टी की जाँच करनी चाहिए। 2. जब पासवर्ड null या empty होता है, यह मेथड false लौटाता है. |

**वापसी:**
boolean - True यदि प्रस्तुति लिखने के लिए संरक्षित है और पासवर्ड सही है। अन्यथा false।

### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

बाइंडेड प्रस्तुति की दस्तावेज़ गुण प्राप्त करता है।

**वापसी:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

बाइंडेड प्रस्तुति के गुण अपडेट करता है।

--------------------

> ```
> यह उदाहरण दिखाता है कि #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) मेथड को कैसे कॉल किया जाए
>   डाक्यूमेंट प्रॉपर्टीज़ को अपडेट करें जो #readDocumentProperties.readDocumentProperties मेथड के कॉल द्वारा लौटाए गए हैं।
>   
>   IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>   IDocumentProperties props = info.readDocumentProperties();
>   props.setSubject("New subject");
>   props.setLastSavedTime(Calendar.getInstance().getTime());
>   info.updateDocumentProperties(props);
>   info.writeBindedPresentation("new_pres.pptx");
> ```


**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

बाइंडेड प्रस्तुति को स्ट्रीम में लिखता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | स्ट्रीम को सिखने योग्य और लिखने योग्य होना चाहिए। |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

बाइंडेड प्रस्तुति को फ़ाइल में लिखता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| file | java.lang.String | प्रस्तुति फ़ाइल। |