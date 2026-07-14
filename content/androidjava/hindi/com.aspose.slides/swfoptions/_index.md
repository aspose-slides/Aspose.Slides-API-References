---
title: SwfOptions
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: ऐसे विकल्प प्रदान करता है जो नियंत्रित करते हैं कि प्रस्तुति को Swf फ़ॉर्मेट में कैसे सहेजा जाता है।
type: docs
url: /hi/com.aspose.slides/swfoptions/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

प्रेज़ेंटेशन को Swf फ़ॉर्मेट में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // एक Presentation ऑब्जेक्ट बना रहे हैं जो एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // प्रस्तुति और नोट्स पृष्ठ सहेज रहे हैं
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | डिफ़ॉल्ट कंस्ट्रक्टर। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | निर्धारित करता है कि जनित दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | निर्धारित करता है कि जनित दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। |
| [getCompressed()](#getCompressed--) | निर्धारित करता है कि जनित SWF दस्तावेज़ को संकुचित किया जाएगा या नहीं। |
| [setCompressed(boolean value)](#setCompressed-boolean-) | निर्धारित करता है कि जनित SWF दस्तावेज़ को संकुचित किया जाएगा या नहीं। |
| [getViewerIncluded()](#getViewerIncluded--) | निर्धारित करता है कि जनित SWF दस्तावेज़ में एकीकृत दस्तावेज़ व्यूअर शामिल होगा या नहीं। |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | निर्धारित करता है कि जनित SWF दस्तावेज़ में एकीकृत दस्तावेज़ व्यूअर शामिल होगा या नहीं। |
| [getShowPageBorder()](#getShowPageBorder--) | पृष्ठों के चारों ओर बॉर्डर दिखाया जाना चाहिए या नहीं, यह निर्धारित करता है। |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | पृष्ठों के चारों ओर बॉर्डर दिखाया जाना चाहिए या नहीं, यह निर्धारित करता है। |
| [getShowFullScreen()](#getShowFullScreen--) | फ़ुल-स्क्रीन बटन दिखाएँ/छुपाएँ। |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | फ़ुल-स्क्रीन बटन दिखाएँ/छुपाएँ। |
| [getShowPageStepper()](#getShowPageStepper--) | पेज़ स्टेपर दिखाएँ/छुपाएँ। |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | पेज़ स्टेपर दिखाएँ/छुपाएँ। |
| [getShowSearch()](#getShowSearch--) | खोज सेक्शन दिखाएँ/छुपाएँ। |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | खोज सेक्शन दिखाएँ/छुपाएँ। |
| [getShowTopPane()](#getShowTopPane--) | पूरी शीर्ष पेन दिखाएँ/छुपाएँ। |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | पूरी शीर्ष पेन दिखाएँ/छुपाएँ। |
| [getShowBottomPane()](#getShowBottomPane--) | नीचे पेन दिखाएँ/छुपाएँ। |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | नीचे पेन दिखाएँ/छुपाएँ। |
| [getShowLeftPane()](#getShowLeftPane--) | बाएँ पेन दिखाएँ/छुपाएँ। |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | बाएँ पेन दिखाएँ/छुपाएँ। |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | बाएँ पेन खुला हुआ स्थित करके शुरू करें। |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | बाएँ पेन खुला हुआ स्थित करके शुरू करें। |
| [getEnableContextMenu()](#getEnableContextMenu--) | कॉन्टेक्ट मेन्यू को सक्षम/अक्षम करें। |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | कॉन्टेक्ट मेन्यू को सक्षम/अक्षम करें। |
| [getLogoImageBytes()](#getLogoImageBytes--) | व्यूअर के शीर्ष-दायीं कोने में लोगो के रूप में दिखाया जाएगा ऐसा चित्र। |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | व्यूअर के शीर्ष-दायीं कोने में लोगो के रूप में दिखाया जाएगा ऐसा चित्र। |
| [getLogoLink()](#getLogoLink--) | लोगो के लिए पूर्ण हाइपरलिंक पता प्राप्त करता है या सेट करता है। |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | लोगो के लिए पूर्ण हाइपरलिंक पता प्राप्त करता है या सेट करता है। |
| [getJpegQuality()](#getJpegQuality--) | JPEG चित्रों की गुणवत्ता निर्धारित करता है। |
| [setJpegQuality(int value)](#setJpegQuality-int-) | JPEG चित्रों की गुणवत्ता निर्धारित करता है। |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | प्राप्त करता है या सेट करता है वह मोड जिसमें स्लाइड्स पृष्ठ पर रखी जाती हैं जब प्रस्तुति निर्यात की जाती है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | प्राप्त करता है या सेट करता है वह मोड जिसमें स्लाइड्स पृष्ठ पर रखी जाती हैं जब प्रस्तुति निर्यात की जाती है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
### SwfOptions() {#SwfOptions--}}
```
public SwfOptions()
```


डिफ़ॉल्ट कंस्ट्रक्टर।

### getShowHiddenSlides() {#getShowHiddenSlides--}}
```
public final boolean getShowHiddenSlides()
```


निर्धारित करता है कि जनित दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। डिफ़ॉल्ट false है।

**वापसी:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


निर्धारित करता है कि जनित दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। डिफ़ॉल्ट false है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}}
```
public final boolean getCompressed()
```


निर्धारित करता है कि जनित SWF दस्तावेज़ को संकुचित किया जाएगा या नहीं। डिफ़ॉल्ट true है।

**वापसी:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```


निर्धारित करता है कि जनित SWF दस्तावेज़ को संकुचित किया जाएगा या नहीं। डिफ़ॉल्ट true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}}
```
public final boolean getViewerIncluded()
```


निर्धारित करता है कि जनित SWF दस्तावेज़ में एकीकृत दस्तावेज़ व्यूअर शामिल होगा या नहीं। डिफ़ॉल्ट true है।

**वापसी:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```


निर्धारित करता है कि जनित SWF दस्तावेज़ में एकीकृत दस्तावेज़ व्यूअर शामिल होगा या नहीं। डिफ़ॉल्ट true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}}
```
public final boolean getShowPageBorder()
```


निर्धारित करता है कि पृष्ठों के चारों ओर बॉर्डर दिखाया जाना चाहिए या नहीं। डिफ़ॉल्ट true है।

**वापसी:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```


निर्धारित करता है कि पृष्ठों के चारों ओर बॉर्डर दिखाया जाना चाहिए या नहीं। डिफ़ॉल्ट true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}}
```
public final boolean getShowFullScreen()
```


फ़ुल-स्क्रीन बटन दिखाएँ/छुपाएँ। इसे flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है।

**वापसी:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```


फ़ुल-स्क्रीन बटन दिखाएँ/छुपाएँ। इसे flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}}
```
public final boolean getShowPageStepper()
```


पेज़ स्टेपर दिखाएँ/छुपाएँ। इसे flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है।

**वापसी:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```


पेज़ स्टेपर दिखाएँ/छुपाएँ। इसे flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}}
```
public final boolean getShowSearch()
```


खोज सेक्शन दिखाएँ/छुपाएँ। इसे flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है।

**वापसी:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```


खोज सेक्शन दिखाएँ/छुपाएँ। इसे flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}}
```
public final boolean getShowTopPane()
```


पूरी शीर्ष पेन दिखाएँ/छुपाएँ। इसे flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है।

**वापसी:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```


पूरी शीर्ष पेन दिखाएँ/छुपाएँ। इसे flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}}
```
public final boolean getShowBottomPane()
```


नीचे पेन दिखाएँ/छुपाएँ। इसे flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है।

**वापसी:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```


नीचे पेन दिखाएँ/छुपाएँ। इसे flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}}
```
public final boolean getShowLeftPane()
```


बाएँ पेन दिखाएँ/छुपाएँ। इसे flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है।

**वापसी:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```


बाएँ पेन दिखाएँ/छुपाएँ। इसे flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}}
```
public final boolean getStartOpenLeftPane()
```


बाएँ पेन खुला हुआ स्थित करके शुरू करें। इसे flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट false है।

**वापसी:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```


बाएँ पेन खुला हुआ स्थित करके शुरू करें। इसे flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट false है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}}
```
public final boolean getEnableContextMenu()
```


कॉन्टेक्ट मेन्यू को सक्षम/अक्षम करें। डिफ़ॉल्ट true है।

**वापसी:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```


कॉन्टेक्ट मेन्यू को सक्षम/अक्षम करें। डिफ़ॉल्ट true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}}
```
public final byte[] getLogoImageBytes()
```


व्यूअर के शीर्ष-दायीं कोने में लोगो के रूप में दिखाया जाएगा ऐसा चित्र। चित्र 32x64 पिक्सेल PNG होना चाहिए, अन्यथा लोगो ठीक से नहीं दिख सकता।

**वापसी:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```


व्यूअर के शीर्ष-दायीं कोने में लोगो के रूप में दिखाया जाएगा ऐसा चित्र। चित्र 32x64 पिक्सेल PNG होना चाहिए, अन्यथा लोगो ठीक से नहीं दिख सकता।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}}
```
public final String getLogoLink()
```


लोगो के लिए पूर्ण हाइपरलिंक पता प्राप्त करता है या सेट करता है। इसका प्रभाव केवल तब पड़ता है जब (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) निर्दिष्ट किया गया हो।

**वापसी:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```


लोगो के लिए पूर्ण हाइपरलिंक पता प्राप्त करता है या सेट करता है। इसका प्रभाव केवल तब पड़ता है जब (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) निर्दिष्ट किया गया हो।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}}
```
public final int getJpegQuality()
```


JPEG चित्रों की गुणवत्ता निर्धारित करता है। डिफ़ॉल्ट 95 है।

**वापसी:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```


JPEG चित्रों की गुणवत्ता निर्धारित करता है। डिफ़ॉल्ट 95 है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


प्राप्त करता है या सेट करता है वह मोड जिसमें स्लाइड्स पृष्ठ पर रखी जाती हैं जब प्रस्तुति निर्यात की जाती है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। इस प्रॉपर्टी को प्रकार [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) के ऑब्जेक्ट असाइन करने का समर्थन नहीं है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


प्राप्त करता है या सेट करता है वह मोड जिसमें स्लाइड्स पृष्ठ पर रखी जाती हैं जब प्रस्तुति निर्यात की जाती है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। इस प्रॉपर्टी को प्रकार [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) के ऑब्जेक्ट असाइन करने का समर्थन नहीं है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |