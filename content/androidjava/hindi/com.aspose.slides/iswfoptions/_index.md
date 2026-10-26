---
title: ISwfOptions
second_title: Aspose.Slides for Android के लिये Java API संदर्भ
description: विकल्प प्रदान करता है जो नियंत्रित करते हैं कि प्रस्तुति SWF स्वरूप में कैसे सहेजी जाती है।
type: docs
url: /hi/com.aspose.slides/iswfoptions/
---
**सभी लागू किए गए इंटरफ़ेस:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

Provides options that control how a presentation is saved in SWF format.
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCompressed()](#getCompressed--) | निर्दिष्ट करता है कि उत्पन्न SWF दस्तावेज़ संकुचित होना चाहिए या नहीं। |
| [setCompressed(boolean value)](#setCompressed-boolean-) | निर्दिष्ट करता है कि उत्पन्न SWF दस्तावेज़ संकुचित होना चाहिए या नहीं। |
| [getViewerIncluded()](#getViewerIncluded--) | निर्दिष्ट करता है कि उत्पन्न SWF दस्तावेज़ में अंतर्निहित दस्तावेज़ व्यूअर शामिल होना चाहिए या नहीं। |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | निर्दिष्ट करता है कि उत्पन्न SWF दस्तावेज़ में अंतर्निहित दस्तावेज़ व्यूअर शामिल होना चाहिए या नहीं। |
| [getShowPageBorder()](#getShowPageBorder--) | निर्दिष्ट करता है कि पृष्ठों के चारों ओर सीमा दिखानी चाहिए या नहीं। |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | निर्दिष्ट करता है कि पृष्ठों के चारों ओर सीमा दिखानी चाहिए या नहीं। |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होनी चाहिए या नहीं। |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होनी चाहिए या नहीं। |
| [getShowFullScreen()](#getShowFullScreen--) | फ़ुलस्क्रीन बटन दिखाएँ/छिपाएँ। |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | फ़ुलस्क्रीन बटन दिखाएँ/छिपाएँ। |
| [getShowPageStepper()](#getShowPageStepper--) | पेज स्टेपर दिखाएँ/छिपाएँ। |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | पेज स्टेपर दिखाएँ/छिपाएँ। |
| [getShowSearch()](#getShowSearch--) | खोज अनुभाग दिखाएँ/छिपाएँ। |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | खोज अनुभाग दिखाएँ/छिपाएँ। |
| [getShowTopPane()](#getShowTopPane--) | पूरे शीर्ष पैन को दिखाएँ/छिपाएँ। |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | पूरे शीर्ष पैन को दिखाएँ/छिपाएँ। |
| [getShowBottomPane()](#getShowBottomPane--) | निचला पैन दिखाएँ/छिपाएँ। |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | निचला पैन दिखाएँ/छिपाएँ। |
| [getShowLeftPane()](#getShowLeftPane--) | बायाँ पैन दिखाएँ/छिपाएँ। |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | बायाँ पैन दिखाएँ/छिपाएँ। |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | बायाँ पैन खुला हुआ शुरू करें। |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | बायाँ पैन खुला हुआ शुरू करें। |
| [getEnableContextMenu()](#getEnableContextMenu--) | संदर्भ मेनू सक्षम/अक्षम करें। |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | संदर्भ मेनू सक्षम/अक्षम करें। |
| [getLogoImageBytes()](#getLogoImageBytes--) | शीर्ष दाएँ कोने में दर्शक के लिए लोगो के रूप में दिखने वाली छवि। |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | शीर्ष दाएँ कोने में दर्शक के लिए लोगो के रूप में दिखने वाली छवि। |
| [getLogoLink()](#getLogoLink--) | लोगो के लिए पूर्ण हाइपरलिंक पता प्राप्त करता है या सेट करता है। |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | लोगो के लिए पूर्ण हाइपरलिंक पता प्राप्त करता है या सेट करता है। |
| [getJpegQuality()](#getJpegQuality--) | JPEG छवियों की गुणवत्ता निर्दिष्ट करता है। |
| [setJpegQuality(int value)](#setJpegQuality-int-) | JPEG छवियों की गुणवत्ता निर्दिष्ट करता है। |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

निर्दिष्ट करता है कि उत्पन्न SWF दस्तावेज़ संकुचित होना चाहिए या नहीं। डिफ़ॉल्ट मान true है।

**रिटर्न:**
boolean

### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

निर्दिष्ट करता है कि उत्पन्न SWF दस्तावेज़ संकुचित होना चाहिए या नहीं। डिफ़ॉल्ट मान true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

निर्दिष्ट करता है कि उत्पन्न SWF दस्तावेज़ में अंतर्निहित दस्तावेज़ व्यूअर शामिल होना चाहिए या नहीं। डिफ़ॉल्ट मान true है।

**रिटर्न:**
boolean

### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

निर्दिष्ट करता है कि उत्पन्न SWF दस्तावेज़ में अंतर्निहित दस्तावेज़ व्यूअर शामिल होना चाहिए या नहीं। डिफ़ॉल्ट मान true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

निर्दिष्ट करता है कि पृष्ठों के चारों ओर सीमा दिखानी चाहिए या नहीं। डिफ़ॉल्ट मान true है।

**रिटर्न:**
boolean

### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

निर्दिष्ट करता है कि पृष्ठों के चारों ओर सीमा दिखानी चाहिए या नहीं। डिफ़ॉल्ट मान true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होनी चाहिए या नहीं। डिफ़ॉल्ट मान false है।

**रिटर्न:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होनी चाहिए या नहीं। डिफ़ॉल्ट मान false है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

फ़ुलस्क्रीन बटन दिखाएँ/छिपाएँ। फ़्लैशवेर में ओवरराइड किया जा सकता है। डिफ़ॉल्ट मान true है।

**रिटर्न:**
boolean

### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

फ़ुलस्क्रीन बटन दिखाएँ/छिपाएँ। फ़्लैशवेर में ओवरराइड किया जा सकता है। डिफ़ॉल्ट मान true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

पेज स्टेपर दिखाएँ/छिपाएँ। फ़्लैशवेर में ओवरराइड किया जा सकता है। डिफ़ॉल्ट मान true है।

**रिटर्न:**
boolean

### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

पेज स्टेपर दिखाएँ/छिपाएँ। फ़्लैशवेर में ओवरराइड किया जा सकता है। डिफ़ॉल्ट मान true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

खोज अनुभाग दिखाएँ/छिपाएँ। फ़्लैशवेर में ओवरराइड किया जा सकता है। डिफ़ॉल्ट मान true है।

**रिटर्न:**
boolean

### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

खोज अनुभाग दिखाएँ/छिपाएँ। फ़्लैशवेर में ओवरराइड किया जा सकता है। डिफ़ॉल्ट मान true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

पूरा शीर्ष पैन दिखाएँ/छिपाएँ। फ़्लैशवेर में ओवरराइड किया जा सकता है। डिफ़ॉल्ट मान true है।

**रिटर्न:**
boolean

### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

पूरा शीर्ष पैन दिखाएँ/छिपाएँ। फ़्लैशवेर में ओवरराइड किया जा सकता है। डिफ़ॉल्ट मान true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

निचला पैन दिखाएँ/छिपाएँ। फ़्लैशवेर में ओवरराइड किया जा सकता है। डिफ़ॉल्ट मान true है।

**रिटर्न:**
boolean

### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

निचला पैन दिखाएँ/छिपाएँ। फ़्लैशवेर में ओवरराइड किया जा सकता है। डिफ़ॉल्ट मान true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

बायाँ पैन दिखाएँ/छिपाएँ। फ़्लैशवेर में ओवरराइड किया जा सकता है। डिफ़ॉल्ट मान true है।

**रिटर्न:**
boolean

### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

बायाँ पैन दिखाएँ/छिपाएँ। फ़्लैशवेर में ओवरराइड किया जा सकता है। डिफ़ॉल्ट मान true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

बायाँ पैन खुला हुआ शुरू करें। फ़्लैशवेर में ओवरराइड किया जा सकता है। डिफ़ॉल्ट मान false है।

**रिटर्न:**
boolean

### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

बायाँ पैन खुला हुआ शुरू करें। फ़्लैशवेर में ओवरराइड किया जा सकता है। डिफ़ॉल्ट मान false है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

संदर्भ मेनू सक्षम/अक्षम करें। डिफ़ॉल्ट मान true है।

**रिटर्न:**
boolean

### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

संदर्भ मेनू सक्षम/अक्षम करें। डिफ़ॉल्ट मान true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

छवि जो व्यूअर के शीर्ष दाएँ कोने में लोगो के रूप में प्रदर्शित होगी। छवि 32x64 पिक्सेल PNG होनी चाहिए, अन्यथा लोगो ठीक से प्रदर्शित नहीं हो सकता।

**रिटर्न:**
byte[]

### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

छवि जो व्यूअर के शीर्ष दाएँ कोने में लोगो के रूप में प्रदर्शित होगी। छवि 32x64 पिक्सेल PNG होनी चाहिए, अन्यथा लोगो ठीक से प्रदर्शित नहीं हो सकता।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

लोगो के लिए पूर्ण हाइपरलिंक पता प्राप्त करता है या सेट करता है। केवल तब प्रभावी जब (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) निर्दिष्ट हो।

**रिटर्न:**
java.lang.String

### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

लोगो के लिए पूर्ण हाइपरलिंक पता प्राप्त करता है या सेट करता है। केवल तब प्रभावी जब (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) निर्दिष्ट हो।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

JPEG छवियों की गुणवत्ता निर्दिष्ट करता है। डिफ़ॉल्ट मान 95 है।

**रिटर्न:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

JPEG छवियों की गुणवत्ता निर्दिष्ट करता है। डिफ़ॉल्ट मान 95 है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। यह प्रॉपर्टी प्रकार [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) की ऑब्जेक्ट असाइन करने का समर्थन नहीं करती।

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

**रिटर्न:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है या सेट करता है [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)। यह प्रॉपर्टी प्रकार [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) की ऑब्जेक्ट असाइन करने का समर्थन नहीं करती।

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