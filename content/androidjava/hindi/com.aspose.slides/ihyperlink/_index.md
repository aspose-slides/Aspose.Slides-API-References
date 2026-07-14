---
title: IHyperlink
second_title: Aspose.Slides for Android via Java API Reference
description: हाइपरलिंक का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

हाइपरलिंक का प्रतिनिधित्व करता है।
## Methods

| मेथड | विवरण |
| --- | --- |
| [getActionType()](#getActionType--) | HyperLinkEx की कार्रवाई का प्रकार लौटाता है। |
| [getExternalUrl()](#getExternalUrl--) | बाहरी URL निर्दिष्ट करता है। यदि यह प्रॉपर्टी null नहीं होती है तो प्रॉपर्टी TargetSlide null हो जाता है। |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | एक हाइपरलिंक का प्रतिनिधित्व करता है जो इस भाग के लिए सेट किया गया है, भाग की वास्तविक सामग्री की परवाह किए बिना। |
| [getTargetSlide()](#getTargetSlide--) | यदि HyperlinkEx विशिष्ट स्लाइड को लक्ष्य बनाता है तो यह स्लाइड लौटाता है। |
| [getTargetFrame()](#getTargetFrame--) | जब मौजूद हो, पैरेंट हाइपरलिंक के टार्गेट के लिए पैरेंट HTML फ्रेमसेट के भीतर फ्रेम लौटाता है। |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | जब मौजूद हो, पैरेंट हाइपरलिंक के टार्गेट के लिए पैरेंट HTML फ्रेमसेट के भीतर फ्रेम लौटाता है। |
| [getTooltip()](#getTooltip--) | एक स्ट्रिंग लौटाता है जिसे यूज़र इंटरफ़ेस में पैरेंट हाइपरलिंक के साथ जुड़े रूप में दिखाया जा सकता है। |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | एक स्ट्रिंग लौटाता है जिसे यूज़र इंटरफ़ेस में पैरेंट हाइपरलिंक के साथ जुड़े रूप में दिखाया जा सकता है। |
| [getHistory()](#getHistory--) | निर्धारित करता है कि पैरेंट हाइपरलिंक का लक्ष्य जब सक्रिय किया जाए तो देखे गए हाइपरलिंक्स की सूची में जोड़ा जाना चाहिए या नहीं। |
| [setHistory(boolean value)](#setHistory-boolean-) | निर्धारित करता है कि पैरेंट हाइपरलिंक का लक्ष्य जब सक्रिय किया जाए तो देखे गए हाइपरलिंक्स की सूची में जोड़ा जाना चाहिए या नहीं। |
| [getHighlightClick()](#getHighlightClick--) | निर्धारित करता है कि क्लिक पर हाइपरलिंक को हाइलाइट किया जाना चाहिए या नहीं। |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | निर्धारित करता है कि क्लिक पर हाइपरलिंक को हाइलाइट किया जाना चाहिए या नहीं। |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | निर्धारित करता है कि हाइपरलिंक क्लिक पर ध्वनि को रोकना चाहिए या नहीं। |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | निर्धारित करता है कि हाइपरलिंक क्लिक पर ध्वनि को रोकना चाहिए या नहीं। |
| [getSound()](#getSound--) | हाइपरलिंक के चल रहे ध्वनि का प्रतिनिधित्व करता है। |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | हाइपरलिंक के चल रहे ध्वनि का प्रतिनिधित्व करता है। |
| [getColorSource()](#getColorSource--) | हाइपरलिंक रंग का स्रोत दर्शाता है - या तो स्टाइल्स या भाग स्वरूप। |
| [setColorSource(int value)](#setColorSource-int-) | हाइपरलिंक रंग का स्रोत दर्शाता है - या तो स्टाइल्स या भाग स्वरूप। |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | निर्धारित करता है कि दो Hyperlink इंस्टेंसेज़ समान हैं या नहीं। |
### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

HyperLinkEx की कार्रवाई का प्रकार लौटाता है। केवल पढ़ने योग्य [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype)।

**वापसी:**
int
### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

बाहरी URL निर्दिष्ट करता है। यदि यह प्रॉपर्टी null नहीं होती है तो प्रॉपर्टी TargetSlide null हो जाता है। केवल पढ़ने योग्य String।

**वापसी:**
java.lang.String
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

एक हाइपरलिंक का प्रतिनिधित्व करता है जो इस भाग के लिए सेट किया गया है, भाग की वास्तविक सामग्री की परवाह किए बिना।

--------------------

PowerPoint लिंक और उनके संबंधित टेक्स्ट को भाग में विशेष रूप से प्रोसेस करता है। यह हाइपरलिंक के लिए वैध URL के रूप में टेक्स्ट बनाने की अनुमति देता है, जो लिंक के वास्तविक पते से भिन्न हो सकता है। इस स्थिति में, जब आप संपादन विंडो में लिंक देखेंगे, तो यह टेक्स्ट भाग से मेल रखने के लिए बदल दिया जाएगा। यह प्रॉपर्टी हाइपरलिंक के मूल मान को दर्शाती है।

**वापसी:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

यदि HyperlinkEx विशिष्ट स्लाइड को लक्ष्य बनाता है तो यह स्लाइड लौटाता है। यदि प्रॉपर्टी null नहीं होती है तो प्रॉपर्टी ExternalUrl null हो जाता है। केवल पढ़ने योग्य [ISlide](../../com.aspose.slides/islide)।

**वापसी:**
[ISlide](../../com.aspose.slides/islide)
### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

जब मौजूद हो, पैरेंट हाइपरलिंक के टार्गेट के लिए पैरेंट HTML फ्रेमसेट के भीतर फ्रेम लौटाता है। पढ़ने/लिखने योग्य String।

**वापसी:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

जब मौजूद हो, पैरेंट हाइपरलिंक के टार्गेट के लिए पैरेंट HTML फ्रेमसेट के भीतर फ्रेम लौटाता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

एक स्ट्रिंग लौटाता है जिसे यूज़र इंटरफ़ेस में पैरेंट हाइपरलिंक के साथ जुड़े रूप में दिखाया जा सकता है। पढ़ने/लिखने योग्य String।

**वापसी:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

एक स्ट्रिंग लौटाता है जिसे यूज़र इंटरफ़ेस में पैरेंट हाइपरलिंक के साथ जुड़े रूप में दिखाया जा सकता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

निर्धारित करता है कि पैरेंट हाइपरलिंक का लक्ष्य जब सक्रिय किया जाए तो देखे गए हाइपरलिंक्स की सूची में जोड़ा जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**वापसी:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

निर्धारित करता है कि पैरेंट हाइपरलिंक का लक्ष्य जब सक्रिय किया जाए तो देखे गए हाइपरलिंक्स की सूची में जोड़ा जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

निर्धारित करता है कि क्लिक पर हाइपरलिंक को हाइलाइट किया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**वापसी:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

निर्धारित करता है कि क्लिक पर हाइपरलिंक को हाइलाइट किया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

निर्धारित करता है कि हाइपरलिंक क्लिक पर ध्वनि को रोकना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**वापसी:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

निर्धारित करता है कि हाइपरलिंक क्लिक पर ध्वनि को रोकना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

हाइपरलिंक के चल रहे ध्वनि का प्रतिनिधित्व करता है। पढ़ने/लिखने योग्य [IAudio](../../com.aspose.slides/iaudio)।

--------------------

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
>          // हाइपरलिंक की ध्वनि को बाइट एरे में निकालें
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
public abstract void setSound(IAudio value)
```

हाइपरलिंक के चल रहे ध्वनि का प्रतिनिधित्व करता है। पढ़ने/लिखने योग्य [IAudio](../../com.aspose.slides/iaudio)।

--------------------

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getColorSource() {#getColorSource--}
```
public abstract int getColorSource()
```

हाइपरलिंक रंग का स्रोत दर्शाता है - या तो स्टाइल्स या भाग स्वरूप। पढ़ने/लिखने योग्य [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)।

**वापसी:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

हाइपरलिंक रंग का स्रोत दर्शाता है - या तो स्टाइल्स या भाग स्वरूप। पढ़ने/लिखने योग्य [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```

निर्धारित करता है कि दो Hyperlink इंस्टेंसेज़ समान हैं या नहीं।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | तुलना के लिए वर्तमान Hyperlink से Hyperlink। |

**वापसी:**
boolean - **true** यदि निर्दिष्ट Hyperlink वर्तमान Hyperlink के समान है; अन्यथा **false**।