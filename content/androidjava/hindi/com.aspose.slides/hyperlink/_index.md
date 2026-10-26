---
title: Hyperlink
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
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
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | हाइपरलिंक का एक उदाहरण बनाता है। |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | हाइपरलिंक का एक उदाहरण बनाता है जो विशिष्ट स्लाइड की ओर इंगित करता है। |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | हाइपरलिंक का एक उदाहरण बनाता है जो अन्य हाइपरलिंक को स्रोत के रूप में उपयोग करता है, द्वितीयक गुणों को ओवरराइड करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | एक विशेष "कुछ न करें" हाइपरलिंक लौटाता है। |
| [getMedia()](#getMedia--) | एक विशेष "मीडिया फ़ाइल चलाएँ" हाइपरलिंक लौटाता है। |
| [getNextSlide()](#getNextSlide--) | अगले स्लाइड का हाइपरलिंक लौटाता है। |
| [getPreviousSlide()](#getPreviousSlide--) | पिछले स्लाइड का हाइपरलिंक लौटाता है। |
| [getFirstSlide()](#getFirstSlide--) | प्रेजेंटेशन की पहली स्लाइड का हाइपरलिंक लौटाता है। |
| [getLastSlide()](#getLastSlide--) | प्रेजेंटेशन की आखिरी स्लाइड का हाइपरलिंक लौटाता है। |
| [getLastVievedSlide()](#getLastVievedSlide--) | आखिरी देखी गई स्लाइड का हाइपरलिंक लौटाता है। |
| [getEndShow()](#getEndShow--) | ऐसा हाइपरलिंक लौटाता है जो शो को समाप्त करता है। |
| [getActionType()](#getActionType--) | हाइपरलिंक की कार्रवाई का प्रकार लौटाता है। |
| [getExternalUrl()](#getExternalUrl--) | बाहरी URL निर्दिष्ट करता है। |
| [getTargetSlide()](#getTargetSlide--) | यदि हाइपरलिंक विशिष्ट स्लाइड को लक्षित करता है तो यह स्लाइड लौटाता है। |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | एक हाइपरलिंक को दर्शाता है जो इस भाग के लिए सेट किया गया है बिना भाग की वास्तविक सामग्री को ध्यान में रखे। |
| [getTargetFrame()](#getTargetFrame--) | जब मौजूद हो, तो पैरेंट हाइपरलिंक के टार्गेट के लिए पैरेंट HTML फ्रेमसेट के भीतर फ्रेम लौटाता है। |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | जब मौजूद हो, तो पैरेंट हाइपरलिंक के टार्गेट के लिए पैरेंट HTML फ्रेमसेट के भीतर फ्रेम लौटाता है। |
| [getTooltip()](#getTooltip--) | ऐसी स्ट्रिंग लौटाता है जो यूज़र इंटरफ़ेस में पैरेंट हाइपरलिंक से जुड़ी हुई दिख सकती है। |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | ऐसी स्ट्रिंग लौटाता है जो यूज़र इंटरफ़ेस में पैरेंट हाइपरलिंक से जुड़ी हुई दिख सकती है। |
| [getHistory()](#getHistory--) | निर्धारित करता है कि पैरेंट हाइपरलिंक का टार्गेट जब इसे बुलाया जाए तो देखे गए हाइपरलिंक्स की सूची में जोड़ा जाएगा या नहीं। |
| [setHistory(boolean value)](#setHistory-boolean-) | निर्धारित करता है कि पैरेंट हाइपरलिंक का टार्गेट जब इसे बुलाया जाए तो देखे गए हाइपरलिंक्स की सूची में जोड़ा जाएगा या नहीं। |
| [getHighlightClick()](#getHighlightClick--) | निर्धारित करता है कि हाइपरलिंक पर क्लिक करने पर हाइलाइट किया जाना चाहिए या नहीं। |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | निर्धारित करता है कि हाइपरलिंक पर क्लिक करने पर हाइलाइट किया जाना चाहिए या नहीं। |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | निर्धारित करता है कि हाइपरलिंक क्लिक पर आवाज़ रोकनी चाहिए या नहीं। |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | निर्धारित करता है कि हाइपरलिंक क्लिक पर आवाज़ रोकनी चाहिए या नहीं। |
| [getSound()](#getSound--) | हाइपरलिंक की बजती आवाज़ को दर्शाता है। |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | हाइपरलिंक की बजती आवाज़ को दर्शाता है। |
| [getColorSource()](#getColorSource--) | हाइपरलिंक रंग का स्रोत दर्शाता है - या तो स्टाइल्स या भाग का फार्मेट। |
| [setColorSource(int value)](#setColorSource-int-) | हाइपरलिंक रंग का स्रोत दर्शाता है - या तो स्टाइल्स या भाग का फार्मेट। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि दो हाइपरलिंक इंस्टेंस समान हैं या नहीं। |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | निर्धारित करता है कि दो हाइपरलिंक इंस्टेंस समान हैं या नहीं। |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | दो हाइपरलिंक की समानता की जाँच करता है। |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | दो हाइपरलिंक की असमानता की जाँच करता है। |
| [hashCode()](#hashCode--) | विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है, जो हैशिंग एल्गोरिदम और हैश टेबल जैसी डेटा संरचनाओं में उपयोग के योग्य है। |
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

हाइपरलिंक का एक उदाहरण बनाता है जो विशिष्ट स्लाइड की ओर इंगित करता है। ध्यान दें: निर्मित हाइपरलिंक को उसी प्रेजेंटेशन के किसी ऑब्जेक्ट को असाइन किया जाना चाहिए, अन्यथा लिंक NoAction के रूप में सहेजा जाएगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | लक्ष्य स्लाइड। |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

हाइपरलिंक का एक उदाहरण बनाता है जो अन्य हाइपरलिंक को स्रोत के रूप में उपयोग करता है, द्वितीयक गुणों को ओवरराइड करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | स्रोत हाइपरलिंक |
| targetFrame | java.lang.String | टार्गेट फ्रेम |
| tooltip | java.lang.String | टूलटिप टेक्स्ट |
| history | boolean | निर्धारित करता है कि पैरेंट हाइपरलिंक का टार्गेट जब इसे बुलाया जाए तो देखे गए हाइपरलिंक्स की सूची में जोड़ा जाएगा या नहीं। |
| stopSoundsOnClick | boolean | निर्धारित करता है कि हाइपरलिंक क्लिक पर आवाज़ रोकनी चाहिए या नहीं। |
| highlightClick | boolean | निर्धारित करता है कि हाइपरलिंक पर क्लिक करने पर हाइलाइट किया जाना चाहिए या नहीं। |

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने योग्य लॉंग।

**वापसी:**
long
### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

एक विशेष "कुछ न करें" हाइपरलिंक लौटाता है। केवल-पढ़ने योग्य [Hyperlink](../../com.aspose.slides/hyperlink)।

**वापसी:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

एक विशेष "मीडिया फ़ाइल चलाएँ" हाइपरलिंक लौटाता है। AudioFrame और VideoFrame में उपयोग किया जाता है। केवल-पढ़ने योग्य [Hyperlink](../../com.aspose.slides/hyperlink)।

**वापसी:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

अगले स्लाइड का हाइपरलिंक लौटाता है। केवल-पढ़ने योग्य [Hyperlink](../../com.aspose.slides/hyperlink)।

**वापसी:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

पिछले स्लाइड का हाइपरलिंक लौटाता है। केवल-पढ़ने योग्य [Hyperlink](../../com.aspose.slides/hyperlink)।

**वापसी:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

प्रेजेंटेशन की पहली स्लाइड का हाइपरलिंक लौटाता है। केवल-पढ़ने योग्य [Hyperlink](../../com.aspose.slides/hyperlink)।

**वापसी:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

प्रेजेंटेशन की आखिरी स्लाइड का हाइपरलिंक लौटाता है। केवल-पढ़ने योग्य [Hyperlink](../../com.aspose.slides/hyperlink)।

**वापसी:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

आखिरी देखी गई स्लाइड का हाइपरलिंक लौटाता है। केवल-पढ़ने योग्य [Hyperlink](../../com.aspose.slides/hyperlink)।

**वापसी:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

ऐसा हाइपरलिंक लौटाता है जो शो को समाप्त करता है। केवल-पढ़ने योग्य [Hyperlink](../../com.aspose.slides/hyperlink)।

**वापसी:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

हाइपरलिंक की कार्रवाई का प्रकार लौटाता है। केवल-पढ़ने योग्य [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype)।

**वापसी:**
int
### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

बाहरी URL निर्दिष्ट करता है। केवल-पढ़ने योग्य स्ट्रिंग।

**वापसी:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

यदि हाइपरलिंक विशिष्ट स्लाइड को लक्षित करता है तो यह स्लाइड लौटाता है। केवल-पढ़ने योग्य [ISlide](../../com.aspose.slides/islide)।

**वापसी:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

एक हाइपरलिंक को दर्शाता है जो इस भाग के लिए सेट किया गया है बिना भाग की वास्तविक सामग्री को ध्यान में रखे।

PowerPoint लिंक और उनके संबंधित पाठ के साथ एक भाग में विशेष रूप से व्यवहार करता है। यह हाइपरलिंक के लिए वैध URL के रूप में टेक्स्ट बनाने की अनुमति देता है, जो लिंक के वास्तविक पते से अलग होता है। इस स्थिति में, जब आप संपादन विंडो में लिंक देखते हैं, तो यह टेक्स्ट भाग से मिलाने के लिए बदल दिया जाएगा। यह प्रॉपर्टी हाइपरलिंक का मूल मान दर्शाती है।

**वापसी:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

जब मौजूद हो, तो पैरेंट हाइपरलिंक के टार्गेट के लिए पैरेंट HTML फ्रेमसेट के भीतर फ्रेम लौटाता है। केवल-पढ़ने योग्य स्ट्रिंग।

**वापसी:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

जब मौजूद हो, तो पैरेंट हाइपरलिंक के टार्गेट के लिए पैरेंट HTML फ्रेमसेट के भीतर फ्रेम लौटाता है। पढ़ने/लिखने योग्य स्ट्रिंग।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

ऐसी स्ट्रिंग लौटाता है जो यूज़र इंटरफ़ेस में पैरेंट हाइपरलिंक से जुड़ी हुई दिख सकती है। पढ़ने/लिखने योग्य स्ट्रिंग।

**वापसी:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

ऐसी स्ट्रिंग लौटाता है जो यूज़र इंटरफ़ेस में पैरेंट हाइपरलिंक से जुड़ी हुई दिख सकती है। पढ़ने/लिखने योग्य स्ट्रिंग।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

निश्चित करता है कि पैरेंट हाइपरलिंक का टार्गेट जब इसे बुलाया जाए तो देखे गए हाइपरलिंक्स की सूची में जोड़ा जाएगा या नहीं। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

निश्चित करता है कि पैरेंट हाइपरलिंक का टार्गेट जब इसे बुलाया जाए तो देखे गए हाइपरलिंक्स की सूची में जोड़ा जाएगा या नहीं। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

हाइपरलिंक पर क्लिक करने पर हाइलाइट किया जाना चाहिए या नहीं, यह निर्धारित करता है। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

हाइपरलिंक पर क्लिक करने पर हाइलाइट किया जाना चाहिए या नहीं, यह निर्धारित करता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

हाइपरलिंक क्लिक पर आवाज़ रोकनी चाहिए या नहीं, यह निर्धारित करता है। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

हाइपरलिंक क्लिक पर आवाज़ रोकनी चाहिए या नहीं, यह निर्धारित करता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

हाइपरलिंक की बजती आवाज़ को दर्शाता है। पढ़ने/लिखने योग्य [IAudio](../../com.aspose.slides/iaudio)।

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // पहला shape हाइपरलिंक प्राप्त करें
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

**वापसी:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

हाइपरलिंक की बजती आवाज़ को दर्शाता है। पढ़ने/लिखने योग्य [IAudio](../../com.aspose.slides/iaudio)।

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // पहला shape हाइपरलिंक प्राप्त करें
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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

हाइपरलिंक रंग का स्रोत दर्शाता है - या तो स्टाइल्स या भाग का फार्मेट। पढ़ने/लिखने योग्य [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)।

**वापसी:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

हाइपरलिंक रंग का स्रोत दर्शाता है - या तो स्टाइल्स या भाग का फार्मेट। पढ़ने/लिखने योग्य [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

दो हाइपरलिंक इंस्टेंस समान हैं या नहीं, यह निर्धारित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना हेतु वर्तमान हाइपरलिंक। |

**वापसी:**
boolean - **true** यदि निर्दिष्ट हाइपरलिंक वर्तमान हाइपरलिंक के बराबर है; अन्यथा, **false**।
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

दो हाइपरलिंक इंस्टेंस समान हैं या नहीं, यह निर्धारित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | तुलना हेतु वर्तमान हाइपरलिंक। |

**वापसी:**
boolean - **true** यदि निर्दिष्ट हाइपरलिंक वर्तमान हाइपरलिंक के बराबर है; अन्यथा, **false**।
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

दो हाइपरलिंक की समानता की जाँच करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | जाँच हेतु प्रथम हाइपरलिंक। |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | जाँच हेतु द्वितीय हाइपरलिंक। |

**वापसी:**
boolean - **true** यदि हाइपरलिंक समान हैं।
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

दो हाइपरलिंक की असमानता की जाँच करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | जाँच हेतु प्रथम हाइपरलिंक। |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | जाँच हेतु द्वितीय हाइपरलिंक। |

**वापसी:**
boolean - **false** यदि हाइपरलिंक समान हैं।
### hashCode() {#hashCode--}
```
public int hashCode()
```

विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है, जो हैशिंग एल्गोरिदम और हैश टेबल जैसी डेटा संरचनाओं में उपयोग के योग्य है।

**वापसी:**
int - URL के लिए हैश कोड।
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**वापसी:**
com.aspose.slides.IDOMObject