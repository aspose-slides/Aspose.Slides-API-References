---
title: IRowCollection
second_title: Java के लिए Aspose.Slides API संदर्भ
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

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | निर्दिष्ट टेम्पलेट पंक्ति की एक प्रति बनाता है और इसे तालिका के नीचे सम्मिलित करता है। |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | निर्दिष्ट टेम्पलेट पंक्ति की एक प्रति बनाता है और इसे तालिका में निर्दिष्ट स्थान पर सम्मिलित करता है। |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | तालिका से निर्दिष्ट स्थिति पर पंक्ति हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है।

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

निर्दिष्ट टेम्पलेट पंक्ति की एक प्रति बनाता है और इसे तालिका के नीचे सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | टेम्पलेट के रूप में उपयोग की जाने वाली पंक्ति। |
| withAttachedRows | boolean | टेम्पलेट पंक्ति से जुड़ी सभी पंक्तियों को भी कॉपी करने के लिए true। |

**वापसी:**
com.aspose.slides.IRow[] - जोड़ी गयी पंक्तियाँ।
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

निर्दिष्ट टेम्पलेट पंक्ति की एक प्रति बनाता है और इसे तालिका में निर्दिष्ट स्थान पर सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नई पंक्ति का सूचकांक। |
| templ | [IRow](../../com.aspose.slides/irow) | टेम्पलेट के रूप में उपयोग की जाने वाली पंक्ति। |
| withAttachedRows | boolean | टेम्पलेट पंक्ति से जुड़ी सभी पंक्तियों को भी कॉपी करने के लिए true। |

**वापसी:**
com.aspose.slides.IRow[] - सम्मिलित पंक्तियाँ।
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```

तालिका से निर्दिष्ट स्थिति पर पंक्ति हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| firstRowIndex | int | हटाने के लिए पंक्ति का सूचकांक। |
| withAttachedRows | boolean | टेम्पलेट पंक्ति से जुड़ी सभी पंक्तियों को भी हटाने के लिए true। |