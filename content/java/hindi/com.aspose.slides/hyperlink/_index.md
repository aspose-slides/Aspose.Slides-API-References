---
title: Hyperlink
second_title: Aspose.Slides for Java API संदर्भ
description: एक हाइपरलिंक का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/hyperlink/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject  
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

हाइपरलिंक का प्रतिनिधित्व करता है।

## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | हाइपरलिंक का एक उदाहरण बनाता है। |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | एक विशिष्ट स्लाइड की ओर संकेत करने वाला हाइपरलिंक का एक उदाहरण बनाता है। |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | दूसरे हाइपरलिंक को स्रोत के रूप में उपयोग करके, द्वितीयक गुणों को अधिलिखित करते हुए, हाइपरलिंक का एक उदाहरण बनाता है। |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | एक विशेष "do nothing" हाइपरलिंक लौटाता है। |
| [getMedia()](#getMedia--) | एक विशेष "play mediafile" हाइपरलिंक लौटाता है। |
| [getNextSlide()](#getNextSlide--) | अगले स्लाइड का हाइपरलिंक लौटाता है। |
| [getPreviousSlide()](#getPreviousSlide--) | पिछले स्लाइड का हाइपरलिंक लौटाता है। |
| [getFirstSlide()](#getFirstSlide--) | प्रस्तुति के पहले स्लाइड का हाइपरलिंक लौटाता है। |
| [getLastSlide()](#getLastSlide--) | प्रस्तुति के अंतिम स्लाइड का हाइपरलिंक लौटाता है। |
| [getLastVievedSlide()](#getLastVievedSlide--) | अंतिम देखे गए स्लाइड का हाइपरलिंक लौटाता है। |
| [getEndShow()](#getEndShow--) | ऐसे हाइपरलिंक को लौटाता है जो शो को समाप्त करता है। |
| [getActionType()](#getActionType--) | हाइपरलिंक की क्रिया का प्रकार लौटाता है। |
| [getExternalUrl()](#getExternalUrl--) | बाहरी URL निर्धारित करता है। |
| [getTargetSlide()](#getTargetSlide--) | यदि हाइपरलिंक विशिष्ट स्लाइड को लक्षित करता है तो यह स्लाइड लौटाता है। |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | एक हाइपरलिंक का प्रतिनिधित्व करता है जिसे इस भाग के लिए सेट किया गया है बिना भाग की वास्तविक सामग्री को ध्यान में रखे। |
| [getTargetFrame()](#getTargetFrame--) | जब मौजूद हो, पैरेंट हाइपरलिंक के लक्ष्य के लिए पैरेंट HTML फ्रेमसेट के भीतर फ़्रेम लौटाता है। |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | जब मौजूद हो, पैरेंट हाइपरलिंक के लक्ष्य के लिए पैरेंट HTML फ्रेमसेट के भीतर फ़्रेम लौटाता है। |
| [getTooltip()](#getTooltip--) | एक स्ट्रिंग लौटाता है जो उपयोगकर्ता इंटरफ़ेस में पैरेंट हाइपरलिंक से संबद्ध के रूप में प्रदर्शित हो सकती है। |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | एक स्ट्रिंग लौटाता है जो उपयोगकर्ता इंटरफ़ेस में पैरेंट हाइपरलिंक से संबद्ध के रूप में प्रदर्शित हो सकती है। |
| [getHistory()](#getHistory--) | निर्धारित करता है कि क्या पैरेंट हाइपरलिंक का लक्ष्य उसे सक्रिय करने पर देखी गई हाइपरलिंकों की सूची में जोड़ा जाएगा। |
| [setHistory(boolean value)](#setHistory-boolean-) | निर्धारित करता है कि क्या पैरेंट हाइपरलिंक का लक्ष्य उसे सक्रिय करने पर देखी गई हाइपरलिंकों की सूची में जोड़ा जाएगा। |
| [getHighlightClick()](#getHighlightClick--) | निर्धारित करता है कि क्लिक पर हाइपरलिंक को हाइलाइट किया जाना चाहिए या नहीं। |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | निर्धारित करता है कि क्लिक पर हाइपरलिंक को हाइलाइट किया जाना चाहिए या नहीं। |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | निर्धारित करता है कि हाइपरलिंक पर क्लिक करने पर ध्वनि रोकी जानी चाहिए या नहीं। |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | निर्धारित करता है कि हाइपरलिंक पर क्लिक करने पर ध्वनि रोकी जानी चाहिए या नहीं। |
| [getSound()](#getSound--) | हाइपरलिंक की चल रही ध्वनि का प्रतिनिधित्व करता है। |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | हाइपरलिंक की चल रही ध्वनि का प्रतिनिधित्व करता है। |
| [getColorSource()](#getColorSource--) | हाइपरलिंक रंग का स्रोत दर्शाता है - चाहे स्टाइल हो या भाग का फॉर्मेट। |
| [setColorSource(int value)](#setColorSource-int-) | हाइपरलिंक रंग का स्रोत दर्शाता है - चाहे स्टाइल हो या भाग का फॉर्मेट। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि दो हाइपरलिंक इंस्टेंस समान हैं या नहीं। |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | निर्धारित करता है कि दो हाइपरलिंक इंस्टेंस समान हैं या नहीं। |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | दो हाइपरलिंक्स की समानता का परीक्षण करता है। |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | दो हाइपरलिंक्स की असमानता का परीक्षण करता है। |
| [hashCode()](#hashCode--) | एक विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है, हैशिंग एल्गोरिद्म और डेटा संरचनाओं जैसे हैश टेबल में उपयोग के योग्य। |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

हाइपरलिंक का एक उदाहरण बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | java.lang.String | हाइपरलिंक URL। |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

एक विशिष्ट स्लाइड की ओर संकेत करने वाला हाइपरलिंक का एक उदाहरण बनाता है। नोट: निर्मित हाइपरलिंक को उसी प्रस्तुति के कुछ ऑब्जेक्ट को असाइन किया जाना चाहिए, अन्यथा लिंक NoAction के रूप में सहेजा जाएगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | लक्षित स्लाइड। |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

दूसरे हाइपरलिंक को स्रोत के रूप में उपयोग करके, द्वितीयक गुणों को अधिलिखित करते हुए, हाइपरलिंक का एक उदाहरण बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | स्रोत हाइपरलिंक |
| targetFrame | java.lang.String | लक्षित फ्रेम |
| tooltip | java.lang.String | टूलटिप टेक्स्ट |
| history | boolean | निर्धारित करता है कि पैरेंट हाइपरलिंक का लक्ष्य उसे सक्रिय करने पर देखी गई हाइपरलिंकों की सूची में जोड़ा जाएगा। |
| stopSoundsOnClick | boolean | निर्धारित करता है कि हाइपरलिंक पर क्लिक करने पर ध्वनि रोकी जानी चाहिए या नहीं। |
| highlightClick | boolean | निर्धारित करता है कि क्लिक पर हाइपरलिंक को हाइलाइट किया जाना चाहिए या नहीं। |

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल- पढ़ने योग्य लांग।

**रिटर्न:**
long

### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

एक विशेष "do nothing" हाइपरलिंक लौटाता है। केवल- पढ़ने योग्य [Hyperlink](../../com.aspose.slides/hyperlink)।

**रिटर्न:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

एक विशेष "play mediafile" हाइपरलिंक लौटाता है। AudioFrame और VideoFrame में उपयोग किया जाता है। केवल- पढ़ने योग्य [Hyperlink](../../com.aspose.slides/hyperlink)।

**रिटर्न:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

अगले स्लाइड का हाइपरलिंक लौटाता है। केवल- पढ़ने योग्य [Hyperlink](../../com.aspose.slides/hyperlink)।

**रिटर्न:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

पिछले स्लाइड का हाइपरलिंक लौटाता है। केवल- पढ़ने योग्य [Hyperlink](../../com.aspose.slides/hyperlink)।

**रिटर्न:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

प्रस्तुति के पहले स्लाइड का हाइपरलिंक लौटाता है। केवल- पढ़ने योग्य [Hyperlink](../../com.aspose.slides/hyperlink)।

**रिटर्न:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

प्रस्तुति के अंतिम स्लाइड का हाइपरलिंक लौटाता है। केवल- पढ़ने योग्य [Hyperlink](../../com.aspose.slides/hyperlink)।

**रिटर्न:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

अंतिम देखे गए स्लाइड का हाइपरलिंक लौटाता है। केवल- पढ़ने योग्य [Hyperlink](../../com.aspose.slides/hyperlink)।

**रिटर्न:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

ऐसे हाइपरलिंक को लौटाता है जो शो को समाप्त करता है। केवल- पढ़ने योग्य [Hyperlink](../../com.aspose.slides/hyperlink)।

**रिटर्न:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getActionType() {#getActionType--}
```
public final int getActionType()
```

हाइपरलिंक की क्रिया का प्रकार लौटाता है। केवल- पढ़ने योग्य [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype)।

**रिटर्न:**
int

### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

बाहरी URL निर्दिष्ट करता है। केवल- पढ़ने योग्य String।

**रिटर्न:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

यदि हाइपरलिंक विशिष्ट स्लाइड को लक्षित करता है तो यह स्लाइड लौटाता है। केवल- पढ़ने योग्य [ISlide](../../com.aspose.slides/islide)।

**रिटर्न:**
[ISlide](../../com.aspose.slides/islide)

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

एक हाइपरलिंक का प्रतिनिधित्व करता है जिसे इस भाग के लिए सेट किया गया है बिना भाग की वास्तविक सामग्री को ध्यान में रखे।

**रिटर्न:**
java.lang.String

### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

जब मौजूद हो, पैरेंट हाइपरलिंक के लक्ष्य के लिए पैरेंट HTML फ्रेमसेट के भीतर फ़्रेम लौटाता है। पढ़ें/लिखें String।

**रिटर्न:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

जब मौजूद हो, पैरेंट हाइपरलिंक के लक्ष्य के लिए पैरेंट HTML फ्रेमसेट के भीतर फ़्रेम लौटाता है। पढ़ें/लिखें String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

एक स्ट्रिंग लौटाता है जो उपयोगकर्ता इंटरफ़ेस में पैरेंट हाइपरलिंक से संबद्ध के रूप में प्रदर्शित हो सकती है। पढ़ें/लिखें String।

**रिटर्न:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

एक स्ट्रिंग लौटाता है जो उपयोगकर्ता इंटरफ़ेस में पैरेंट हाइपरलिंक से संबद्ध के रूप में प्रदर्शित हो सकती है। पढ़ें/लिखें String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

निर्धारित करता है कि पैरेंट हाइपरलिंक का लक्ष्य उसे सक्रिय करने पर देखी गई हाइपरलिंकों की सूची में जोड़ा जाएगा। पढ़ें/लिखें boolean।

**रिटर्न:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

निर्धारित करता है कि पैरेंट हाइपरलिंक का लक्ष्य उसे सक्रिय करने पर देखी गई हाइपरलिंकों की सूची में जोड़ा जाएगा। पढ़ें/लिखें boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

निर्धारित करता है कि क्लिक पर हाइपरलिंक को हाइलाइट किया जाना चाहिए या नहीं। पढ़ें/लिखें boolean।

**रिटर्न:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

निर्धारित करता है कि क्लिक पर हाइपरलिंक को हाइलाइट किया जाना चाहिए या नहीं। पढ़ें/लिखें boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

निर्धारित करता है कि हाइपरलिंक पर क्लिक करने पर ध्वनि रोकी जानी चाहिए या नहीं। पढ़ें/लिखें boolean।

**रिटर्न:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

निर्धारित करता है कि हाइपरलिंक पर क्लिक करने पर ध्वनि रोकी जानी चाहिए या नहीं। पढ़ें/लिखें boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

हाइपरलिंक की चल रही ध्वनि का प्रतिनिधित्व करता है। पढ़ें/लिखें [IAudio](../../com.aspose.slides/iaudio)।

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // पहला आकार का हाइपरलिंक प्राप्त करें
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // बाइट एरे में हाइपरलिंक ध्वनि निकालें
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**रिटर्न:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

हाइपरलिंक की चल रही ध्वनि का प्रतिनिधित्व करता है। पढ़ें/लिखें [IAudio](../../com.aspose.slides/iaudio)।

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // पहले आकार का हाइपरलिंक प्राप्त करें
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // हाइपरलिंक ध्वनि को बाइट एरे में निकालें
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

हाइपरलिंक रंग का स्रोत दर्शाता है - चाहे स्टाइल हो या भाग का फॉर्मेट। पढ़ें/लिखें [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)।

**रिटर्न:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

हाइपरलिंक रंग का स्रोत दर्शाता है - चाहे स्टाइल हो या भाग का फॉर्मेट। पढ़ें/लिखें [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि दो हाइपरलिंक इंस्टेंस समान हैं या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना के लिए वर्तमान हाइपरलिंक के साथ मिलाने वाला हाइपरलिंक। |

**रिटर्न:**
boolean - **true** यदि निर्दिष्ट हाइपरलिंक वर्तमान हाइपरलिंक के बराबर है; अन्यथा **false**।

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

निर्धारित करता है कि दो हाइपरलिंक इंस्टेंस समान हैं या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | तुलना के लिए वर्तमान हाइपरलिंक के साथ मिलाने वाला हाइपरलिंक। |

**रिटर्न:**
boolean - **true** यदि निर्दिष्ट हाइपरलिंक वर्तमान हाइपरलिंक के बराबर है; अन्यथा **false**।

### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

दो हाइपरलिंक्स की समानता का परीक्षण करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | परीक्षण किया जाने वाला पहला हाइपरलिंक। |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | परीक्षण किया जाने वाला दूसरा हाइपरलिंक। |

**रिटर्न:**
boolean - **true** यदि हाइपरलिंक्स समान हैं।

### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

दो हाइपरलिंक्स की असमानता का परीक्षण करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | परीक्षण किया जाने वाला पहला हाइपरलिंक। |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | परीक्षण किया जाने वाला दूसरा हाइपरलिंक। |

**रिटर्न:**
boolean - **false** यदि हाइपरलिंक्स समान हैं।

### hashCode() {#hashCode--}
```
public int hashCode()
```

एक विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है, हैशिंग एल्गोरिद्म और डेटा संरचनाओं जैसे हैश टेबल में उपयोग के योग्य।

**रिटर्न:**
int - URL के लिए हैश कोड।

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल- पढ़ने योग्य IDOMObject।

**रिटर्न:**
com.aspose.slides.IDOMObject