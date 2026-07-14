---
title: IChartTitle
second_title: Java API रेफ़रेंस के माध्यम से Android के लिये Aspose.Slides
description: चार्ट शीर्षक गुणों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/icharttitle/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

चार्ट शीर्षक गुणों का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getOverlay()](#getOverlay--) | निर्धारित करता है कि क्या अन्य चार्ट तत्वों को शीर्षक के साथ ओवरलैप करने की अनुमति होगी। |
| [setOverlay(boolean value)](#setOverlay-boolean-) | निर्धारित करता है कि क्या अन्य चार्ट तत्वों को शीर्षक के साथ ओवरलैप करने की अनुमति होगी। |
| [getFormat()](#getFormat--) | शीर्षक की भराव, रेखा, प्रभाव स्टाइल लौटाता है। |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


निर्धारित करता है कि क्या अन्य चार्ट तत्वों को शीर्षक के साथ ओवरलैप करने की अनुमति होगी। पढ़ने/लिखने योग्य boolean.

**रिटर्न:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


निर्धारित करता है कि क्या अन्य चार्ट तत्वों को शीर्षक के साथ ओवरलैप करने की अनुमति होगी। पढ़ने/लिखने योग्य boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


शीर्षक की भराव, रेखा, प्रभाव स्टाइल लौटाता है। केवल-पढ़ने योग्य [IFormat](../../com.aspose.slides/iformat).

**रिटर्न:**
[IFormat](../../com.aspose.slides/iformat)