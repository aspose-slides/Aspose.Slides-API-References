---
title: IHyperlink
second_title: Aspose.Slides for Java API Reference
description: Represents a hyperlink.
type: docs
url: /hi/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

हाइपरलिंक को दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getActionType()](#getActionType--) | HyperLinkEx के कार्य का प्रकार लौटाता है। |
| [getExternalUrl()](#getExternalUrl--) | यदि यह प्रॉपर्टी null नहीं रहती है तो TargetSlide प्रॉपर्टी null हो जाती है। बाहरी URL निर्दिष्ट करता है। |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | भाग की वास्तविक सामग्री की परवाह किए बिना इस भाग के लिए सेट किया गया हाइपरलिंक दर्शाता है। |
| [getTargetSlide()](#getTargetSlide--) | यदि HyperlinkEx विशिष्ट स्लाइड को लक्षित करता है तो वह स्लाइड लौटाता है। |
| [getTargetFrame()](#getTargetFrame--) | जब उपलब्ध हो, पैरेंट हाइपरलिंक के लक्ष्य के लिए पैरेंट HTML फ्रेमसेट के भीतर फ्रेम लौटाता है। |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | जब उपलब्ध हो, पैरेंट हाइपरलिंक के लक्ष्य के लिए पैरेंट HTML फ्रेमसेट के भीतर फ्रेम लौटाता है। |
| [getTooltip()](#getTooltip--) | पैरेंट हाइपरलिंक से संबंधित उपयोगकर्ता इंटरफ़ेस में प्रदर्शित हो सकने वाली स्ट्रिंग लौटाता है। |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | पैरेंट हाइपरलिंक से संबंधित उपयोगकर्ता इंटरफ़ेस में प्रदर्शित हो सकने वाली स्ट्रिंग लौटाता है। |
| [getHistory()](#getHistory--) | निर्धारित करता है कि जब पैरेंट हाइपरलिंक को बुलाया जाए तो उसका लक्ष्य देखी गई हाइपरलिंक्स की सूची में जोड़ा जाना चाहिए या नहीं। |
| [setHistory(boolean value)](#setHistory-boolean-) | निर्धारित करता है कि जब पैरेंट हाइपरलिंक को बुलाया जाए तो उसका लक्ष्य देखी गई हाइपरलिंक्स की सूची में जोड़ा जाना चाहिए या नहीं। |
| [getHighlightClick()](#getHighlightClick--) | निर्धारित करता है कि क्लिक पर हाइपरलिंक को हाइलाइट किया जाना चाहिए या नहीं। |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | निर्धारित करता है कि क्लिक पर हाइपरलिंक को हाइलाइट किया जाना चाहिए या नहीं। |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | निर्धारित करता है कि हाइपरलिंक क्लिक पर ध्वनि को बंद किया जाना चाहिए या नहीं। |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | निर्धारित करता है कि हाइपरलिंक क्लिक पर ध्वनि को बंद किया जाना चाहिए या नहीं। |
| [getSound()](#getSound--) | हाइपरलिंक की चल रही ध्वनि को दर्शाता है। |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | हाइपरलिंक की चल रही ध्वनि को दर्शाता है। |
| [getColorSource()](#getColorSource--) | हाइपरलिंक के रंग स्रोत को दर्शाता है - या तो शैली या भाग स्वरूप। |
| [setColorSource(int value)](#setColorSource-int-) | हाइपरलिंक के रंग स्रोत को दर्शाता है - या तो शैली या भाग स्वरूप। |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | निर्धारित करता है कि दो Hyperlink उदाहरण समान हैं या नहीं। |
### getActionType() {#getActionType--}
```
public abstract int getActionType()
```


HyperLinkEx के कार्य का प्रकार लौटाता है। केवल-पढ़ने योग्य [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype)।

**रिटर्न:**
int
### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```


यदि यह प्रॉपर्टी null नहीं रहती है तो TargetSlide प्रॉपर्टी null हो जाती है। बाहरी URL निर्दिष्ट करता है। केवल-पढ़ने योग्य String।

**रिटर्न:**
java.lang.String
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```


भाग की वास्तविक सामग्री की परवाह किए बिना इस भाग के लिए सेट किया गया हाइपरलिंक दर्शाता है।

--------------------

PowerPoint लिंक और उनके संबंधित भागों के पाठ के लिए विशिष्ट व्यवहार करता है। यह हाइपरलिंक के लिए वैध URL के रूप में पाठ बनाने की अनुमति देता है, जो लिंक के वास्तविक पते से अलग होता है। इस स्थिति में, जब आप संपादन विंडो में लिंक देखते हैं, तो यह पाठ भाग के साथ मिलाने के लिए बदल दिया जाएगा। यह प्रॉपर्टी हाइपरलिंक का मूल मूल्य दर्शाती है।

**रिटर्न:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```


यदि HyperlinkEx विशिष्ट स्लाइड को लक्षित करता है तो वह स्लाइड लौटाता है। यदि यह प्रॉपर्टी null नहीं रहती है तो ExternalUrl प्रॉपर्टी null हो जाती है। केवल-पढ़ने योग्य [ISlide](../../com.aspose.slides/islide)।

**रिटर्न:**
[ISlide](../../com.aspose.slides/islide)
### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```


जब उपलब्ध हो, पैरेंट हाइपरलिंक के लक्ष्य के लिए पैरेंट HTML फ्रेमसेट के भीतर फ्रेम लौटाता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```


जब उपलब्ध हो, पैरेंट हाइपरलिंक के लक्ष्य के लिए पैरेंट HTML फ्रेमसेट के भीतर फ्रेम लौटाता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```


पैरेंट हाइपरलिंक से संबंधित उपयोगकर्ता इंटरफ़ेस में प्रदर्शित हो सकने वाली स्ट्रिंग लौटाता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```


पैरेंट हाइपरलिंक से संबंधित उपयोगकर्ता इंटरफ़ेस में प्रदर्शित हो सकने वाली स्ट्रिंग लौटाता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```


निर्धारित करता है कि जब पैरेंट हाइपरलिंक को बुलाया जाए तो उसका लक्ष्य देखी गई हाइपरलिंक्स की सूची में जोड़ा जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```


निर्धारित करता है कि जब पैरेंट हाइपरलिंक को बुलाया जाए तो उसका लक्ष्य देखी गई हाइपरलिंक्स की सूची में जोड़ा जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```


निर्धारित करता है कि क्लिक पर हाइपरलिंक को हाइलाइट किया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```


निर्धारित करता है कि क्लिक पर हाइपरलिंक को हाइलाइट किया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```


निर्धारित करता है कि हाइपरलिंक क्लिक पर ध्वनि को बंद किया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```


निर्धारित करता है कि हाइपरलिंक क्लिक पर ध्वनि को बंद किया जाना चाहिए या नहीं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


हाइपरलिंक की चल रही ध्वनि को दर्शाता है। पढ़ने/लिखने योग्य [IAudio](../../com.aspose.slides/iaudio)।

--------------------

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
>          // हाइपरलिंक की ध्वनि को बाइट एरे में निकालें
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
public abstract void setSound(IAudio value)
```


हाइपरलिंक की चल रही ध्वनि को दर्शाता है। पढ़ने/लिखने योग्य [IAudio](../../com.aspose.slides/iaudio)।

--------------------

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
>          // हाइपरलिंक की ध्वनि को बाइट एरे में निकालें
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
public abstract int getColorSource()
```


हाइपरलिंक के रंग स्रोत को दर्शाता है - या तो शैली या भाग स्वरूप। पढ़ने/लिखने योग्य [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)।

**रिटर्न:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```


हाइपरलिंक के रंग स्रोत को दर्शाता है - या तो शैली या भाग स्वरूप। पढ़ने/लिखने योग्य [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```


निर्धारित करता है कि दो Hyperlink उदाहरण समान हैं या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | तुलना हेतु Hyperlink। |

**रिटर्न:**
boolean - **true** यदि निर्दिष्ट Hyperlink वर्तमान Hyperlink के समान है; अन्यथा **false**।