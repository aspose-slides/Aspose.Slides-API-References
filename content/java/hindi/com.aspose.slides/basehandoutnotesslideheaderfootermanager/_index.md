---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: Aspose.Slides for Java API संदर्भ
description: प्लेसहोल्डरों के व्यवहार को संभालने वाला प्रबंधक दर्शाता है, जिसमें सभी प्रकार की हैंडआउट और नोट्स स्लाइड्स के लिए हेडर प्लेसहोल्डर शामिल है।
type: docs
url: /hi/com.aspose.slides/basehandoutnotesslideheaderfootermanager/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)  
```
public abstract class BaseHandoutNotesSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IBaseHandoutNotesSlideHeaderFooterManag
```

प्लेसहोल्डरों के व्यवहार को संभालने वाला प्रबंधक दर्शाता है, जिसमें सभी प्रकार की हैंडआउट और नोट्स स्लाइड्स के लिए हेडर प्लेसहोल्डर शामिल है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | हेडर प्लेसहोल्डर मौजूद होने को दर्शाने वाला मान प्राप्त करता है। |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | स्लाइड हेडर प्लेसहोल्डर की दृश्यता बदलता है। |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | स्लाइड हेडर प्लेसहोल्डर को टेक्स्ट सेट करता है। |

### isHeaderVisible() {#isHeaderVisible--}
```
public final boolean isHeaderVisible()
```

हेडर प्लेसहोल्डर मौजूद होने को दर्शाने वाला मान प्राप्त करता है। बूलियन पढ़ें।

**वापसी:**  
boolean

### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public final void setHeaderVisibility(boolean isVisible)
```

स्लाइड हेडर प्लेसहोल्डर की दृश्यता बदलता है।

**पैरामीटर:**  

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - हेडर प्लेसहोल्डर को दिखाता है, अन्यथा - इसे छिपा देता है। |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public final void setHeaderText(String text)
```

स्लाइड हेडर प्लेसहोल्डर को टेक्स्ट सेट करता है।

**पैरामीटर:**  

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए टेक्स्ट। |