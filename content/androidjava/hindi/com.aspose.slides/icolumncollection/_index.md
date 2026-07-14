---
title: IColumnCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक तालिका में कॉलमों का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/icolumncollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

एक तालिका में कॉलमों का संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर कॉलम लौटाता है। |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | निर्दिष्ट टेम्पलेट पंक्ति की एक प्रति बनाता है और उसे तालिका के नीचे सम्मिलित करता है। |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | निर्दिष्ट टेम्पलेट कॉलम की एक प्रति बनाता है और उसे तालिका में निर्दिष्ट स्थान पर सम्मिलित करता है। |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | तालिका से निर्दिष्ट स्थान पर कॉलम हटाता है। |

### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```

निर्दिष्ट इंडेक्स पर कॉलम लौटाता है। केवल-पढ़ने-योग्य [IColumn](../../com.aspose.slides/icolumn)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IColumn](../../com.aspose.slides/icolumn)

### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

निर्दिष्ट टेम्पलेट पंक्ति की एक प्रति बनाता है और उसे तालिका के नीचे सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | टेम्पलेट के रूप में उपयोग किया गया कॉलम। |
| withAttachedColumns | boolean | टेम्पलेट पंक्ति से जुड़े सभी कॉलमों को भी कॉपी करने के लिए True। |

**रिटर्न:**
com.aspose.slides.IColumn[] - जोडें गए कॉलम।

### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

निर्दिष्ट टेम्पलेट कॉलम की एक प्रति बनाता है और उसे तालिका में निर्दिष्ट स्थान पर सम्मिलित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | नए कॉलम का इंडेक्स। |
| templ | [IColumn](../../com.aspose.slides/icolumn) | टेम्पलेट के रूप में उपयोग किया गया कॉलम। |
| withAttachedColumns | boolean | टेम्पलेट कॉलम से जुड़े सभी कॉलमों को भी कॉपी करने के लिए True। |

**रिटर्न:**
com.aspose.slides.IColumn[] - डाली गई कॉलम।

### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

तालिका से निर्दिष्ट स्थान पर कॉलम हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| firstColumnIndex | int | डिलीट किए जाने वाले कॉलम का इंडेक्स। |
| withAttachedRows | boolean | सभी जुड़े कॉलमों को भी डिलीट करने के लिए True। |