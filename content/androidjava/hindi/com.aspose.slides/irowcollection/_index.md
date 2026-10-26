---
title: IRowCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: टेबल पंक्ति संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/irowcollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

टेबल पंक्ति संग्रह का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | निर्दिष्ट टेम्प्लेट पंक्ति की एक कॉपी बनाता है और उसे तालिका के नीचे डालता है। |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | निर्दिष्ट टेम्प्लेट पंक्ति की एक कॉपी बनाता है और उसे तालिका में निर्दिष्ट स्थान पर डालता है। |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | तालिका में निर्दिष्ट स्थान से एक पंक्ति हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```


निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```


निर्दिष्ट टेम्प्लेट पंक्ति की एक कॉपी बनाता है और उसे तालिका के नीचे डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | टेम्पलेट के रूप में उपयोग की जाने वाली पंक्ति। |
| withAttachedRows | boolean | True को टेम्पलेट पंक्ति से जुड़े सभी पंक्तियों को भी कॉपी करने के लिए सेट किया जाता है। |

**वापसी:**
com.aspose.slides.IRow[] - जोड़े गए पंक्तियाँ।
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


निर्दिष्ट टेम्प्लेट पंक्ति की एक कॉपी बनाता है और उसे तालिका में निर्दिष्ट स्थान पर डालता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नई पंक्ति का इंडेक्स। |
| templ | [IRow](../../com.aspose.slides/irow) | टेम्पलेट के रूप में उपयोग की जाने वाली पंक्ति। |
| withAttachedRows | boolean | True को टेम्पलेट पंक्ति से जुड़े सभी पंक्तियों को भी कॉपी करने के लिए सेट किया जाता है। |

**वापसी:**
com.aspose.slides.IRow[] - डाली गई पंक्तियाँ।
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```


तालिका में निर्दिष्ट स्थान से एक पंक्ति हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| firstRowIndex | int | हटाने के लिए पंक्ति का इंडेक्स। |
| withAttachedRows | boolean | True को सभी जुड़े पंक्तियों को भी हटाने के लिए सेट किया जाता है। |