---
title: IColumnCollection
second_title: Aspose.Slides for Java API संदर्भ
description: एक तालिका में स्तंभों का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/icolumncollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

एक तालिका में स्तंभों का संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर स्तंभ लौटाता है। |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | निर्दिष्ट टेम्पलेट पंक्ति की एक प्रतिलिपि बनाता है और उसे तालिका के नीचे सम्मिलित करता है। |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | निर्दिष्ट टेम्पलेट स्तंभ की एक प्रतिलिपि बनाता है और उसे तालिका में निर्दिष्ट स्थिति पर सम्मिलित करता है। |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | तालिका से निर्दिष्ट स्थिति पर एक स्तंभ हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```


निर्दिष्ट अनुक्रमांक पर स्तंभ लौटाता है। केवल-पढ़ने योग्य [IColumn](../../com.aspose.slides/icolumn).

**परामीटर | प्रकार | विवरण**
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


निर्दिष्ट टेम्पलेट पंक्ति की एक प्रतिलिपि बनाता है और उसे तालिका के नीचे सम्मिलित करता है।

**परामीटर | प्रकार | विवरण**
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | टेम्पलेट के रूप में उपयोग किया जाने वाला स्तंभ। |
| withAttachedColumns | boolean | सभी टेम्पलेट पंक्ति से जुड़े स्तंभों को भी कॉपी करने के लिए true। |

**रिटर्न:**
com.aspose.slides.IColumn[] - जोड़े गए स्तंभ।
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


निर्दिष्ट टेम्पलेट स्तंभ की एक प्रतिलिपि बनाता है और उसे तालिका में निर्दिष्ट स्थिति पर सम्मिलित करता है।

**परामीटर | प्रकार | विवरण**
| --- | --- | --- |
| index | int | नई स्तंभ का अनुक्रमांक। |
| templ | [IColumn](../../com.aspose.slides/icolumn) | टेम्पलेट के रूप में उपयोग किया जाने वाला स्तंभ। |
| withAttachedColumns | boolean | सभी टेम्पलेट स्तंभ से जुड़े स्तंभों को भी कॉपी करने के लिए true। |

**रिटर्न:**
com.aspose.slides.IColumn[] - डाले गए स्तंभ।
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


तालिका से निर्दिष्ट स्थिति पर एक स्तंभ हटाता है।

**परामीटर | प्रकार | विवरण**
| --- | --- | --- |
| firstColumnIndex | int | हटाने के लिए स्तंभ का अनुक्रमांक। |
| withAttachedRows | boolean | सभी जुड़े स्तंभों को भी हटाने के लिए true। |