---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides जावा API संदर्भ
description: प्लेसहोल्डरों के व्यवहार को रखने वाले मैनेजर का प्रतिनिधित्व करता है, जिसमें सभी प्रकार के हैंडआउट और नोट्स स्लाइड्स के लिए हेडर प्लेसहोल्डर शामिल है।
type: docs
url: /hi/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

एक प्रबंधक का प्रतिनिधित्व करता है जो प्लेसहोल्डरों के व्यवहार को रखता है, जिसमें सभी प्रकार के हैंडआउट और नोट्स स्लाइड्स के लिए हेडर प्लेसहोल्डर शामिल है।

--------------------

मूल इंटरफ़ेस नाम "IBaseHandoutNotesSlideHeaderFooterManager" को COM संगतता के लिए "IBaseHandoutNotesSlideHeaderFooterManag" में संक्षिप्त किया गया है (टाइप नाम की लंबाई 39 अक्षरों से अधिक नहीं होनी चाहिए)।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Gets value indicating that a header placeholder is present. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Changes slide header placeholder visibility. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Sets text to slide header placeholder. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```

हेडर प्लेसहोल्डर मौजूद होने का संकेत देने वाला मान प्राप्त करता है। बूलियन पढ़ें।

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

स्लाइड हेडर प्लेसहोल्डर में पाठ सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने हेतु पाठ। |