---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides Android के लिए Java API संदर्भ
description: एक प्रबंधक का प्रतिनिधित्व करता है जो प्लेसहोल्डरों के व्यवहार को धारण करता है, जिसमें सभी प्रकार की हैंडआउट और नोट्स स्लाइड्स के लिए हेडर प्लेसहोल्डर शामिल है।
type: docs
url: /hi/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**सभी लागू इंटरफेस:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

एक प्रबंधक का प्रतिनिधित्व करता है जो प्लेसहोल्डर के व्यवहार को रखता है, जिसमें सभी प्रकार की हैंडआउट और नोट्स स्लाइड्स के लिए हेडर प्लेसहोल्डर शामिल है।

--------------------

मूल इंटरफ़ेस नाम "IBaseHandoutNotesSlideHeaderFooterManager" को COM संगतता के लिए "IBaseHandoutNotesSlideHeaderFooterManag" में संक्षिप्त किया गया है (टाइप नाम की लंबाई 39 से अधिक नहीं होनी चाहिए)।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | हेडर प्लेसहोल्डर की मौजूदगी दर्शाने वाला मान प्राप्त करता है। |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | स्लाइड हेडर प्लेसहोल्डर की दृश्यता बदलता है। |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | स्लाइड हेडर प्लेसहोल्डर के लिए टेक्स्ट सेट करता है। |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```

हेडर प्लेसहोल्डर की मौजूदगी दर्शाने वाला मान प्राप्त करता है। बूलियन पढ़ें।

**रिटर्न:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```

स्लाइड हेडर प्लेसहोल्डर की दृश्यता बदलता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - हेडर प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा - इसे छुपाता है। |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```

स्लाइड हेडर प्लेसहोल्डर के लिए टेक्स्ट सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए टेक्स्ट। |