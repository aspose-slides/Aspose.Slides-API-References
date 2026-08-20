---
title: IChartTitle
second_title: Aspose.Slides के लिये Java API संदर्भ
description: चार्ट शीर्षक गुणों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/icharttitle/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

शीर्षक चार्ट की प्रॉपर्टी का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getOverlay()](#getOverlay--) | निर्धारित करता है कि क्या अन्य चार्ट तत्वों को शीर्षक के ऊपर ओवरलैप करने की अनुमति होनी चाहिए। |
| [setOverlay(boolean value)](#setOverlay-boolean-) | निर्धारित करता है कि क्या अन्य चार्ट तत्वों को शीर्षक के ऊपर ओवरलैप करने की अनुमति होनी चाहिए। |
| [getFormat()](#getFormat--) | शीर्षक की भराव, रेखा, प्रभाव शैलियों को लौटाता है। |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


निर्धारित करता है कि क्या अन्य चार्ट तत्वों को शीर्षक के ऊपर ओवरलैप करने की अनुमति होनी चाहिए। पढ़ें/लिखें बूलियन।

**वापसी:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


निर्धारित करता है कि क्या अन्य चार्ट तत्वों को शीर्षक के ऊपर ओवरलैप करने की अनुमति होनी चाहिए। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


शीर्षक की भराव, रेखा, प्रभाव शैलियों को लौटाता है। केवल-पढ़ने योग्य [IFormat](../../com.aspose.slides/iformat)।

**वापसी:**
[IFormat](../../com.aspose.slides/iformat)