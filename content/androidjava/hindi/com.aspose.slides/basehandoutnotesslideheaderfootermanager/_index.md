---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: Aspose.Slides के लिए Android के माध्यम से Java API संदर्भ
description: ऐसे मैनेजर का प्रतिनिधित्व करता है जो प्लेसहोल्डर के व्यवहार को धारण करता है, जिसमें सभी प्रकार के हैंडआउट और नोट्स स्लाइड्स के लिए हेडर प्लेसहोल्डर शामिल है।
type: docs
url: /hi/com.aspose.slides/basehandoutnotesslideheaderfootermanager/
---
**Inheritance:**  
विरासत: java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**All Implemented Interfaces:**  
सभी लागू किए गए इंटरफ़ेस:  
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)  
```
public abstract class BaseHandoutNotesSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IBaseHandoutNotesSlideHeaderFooterManag
```

हैडर प्लेसहोल्डर सहित सभी प्रकार के हैंडआउट और नोट्स स्लाइड्स के लिये व्यवहार को धारण करने वाले प्लेसहोल्डर प्रबंधक का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | हेडर प्लेसहोल्डर मौजूद होने को संकेत करने वाला मान प्राप्त करता है। |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | स्लाइड हेडर प्लेसहोल्डर की दृश्यता बदलता है। |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | स्लाइड हेडर प्लेसहोल्डर में पाठ सेट करता है। |

### isHeaderVisible() {#isHeaderVisible--}
```
public final boolean isHeaderVisible()
```

हेडर प्लेसहोल्डर मौजूद होने को संकेत करने वाला मान प्राप्त करता है। बूलियन पढ़ें।

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
| isVisible | boolean | true - एक हेडर प्लेसहोल्डर को दिखाई देता है, अन्यथा - इसे छुपाता है। |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public final void setHeaderText(String text)
```

स्लाइड हेडर प्लेसहोल्डर में पाठ सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए पाठ। |