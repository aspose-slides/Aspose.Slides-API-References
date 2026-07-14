---
title: Portion
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: पाठ अनुच्छेद के भीतर पाठ के एक भाग का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/portion/
---
**विरासत:**
java.lang.Object

**सभी लागू किए गए इंटरफ़ेस:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

एक पाठ अनुच्छेद के भीतर पाठ के एक भाग का प्रतिनिधित्व करता है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [Portion()](#Portion--) | Portion क्लास का नया उदाहरण प्रारंभ करता है। |
| [Portion(String str)](#Portion-java.lang.String-) | Portion क्लास का नया उदाहरण प्रारंभ करता है। |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Portion क्लास का नया उदाहरण प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है जिसमें स्पष्ट रूप से सेट किए गए फ़ॉर्मेटिंग गुण होते हैं जो पाठ भाग के हैं और कोई विरासत लागू नहीं हुई है। |
| [getText()](#getText--) | एक भाग का सरल टेक्स्ट प्राप्त करता है या सेट करता है। |
| [setText(String value)](#setText-java.lang.String-) | एक भाग का सरल टेक्स्ट प्राप्त करता है या सेट करता है। |
| [getField()](#getField--) | इस भाग का एक फ़ील्ड लौटाता है। |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | इस भाग को स्वचालित रूप से अद्यतन फ़ील्ड में परिवर्तित करता है। |
| [addField(String internalString)](#addField-java.lang.String-) | इस भाग को स्वचालित रूप से अद्यतन फ़ील्ड में परिवर्तित करता है। |
| [removeField()](#removeField--) | इस फ़ील्ड भाग को साधारण भाग में परिवर्तित करता है। |
| [getRect()](#getRect--) | उस आयत के निर्देशांक प्राप्त करता है जो भाग को सीमित करता है। |
| [getCoordinates()](#getCoordinates--) | भाग की शुरुआत के निर्देशांक प्राप्त करता है। |
| [getSlide()](#getSlide--) | पाठ की मातृ स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | पाठ की मातृ प्रस्तुति लौटाता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```

Portion क्लास का नया उदाहरण प्रारंभ करता है।

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

Portion क्लास का नया उदाहरण प्रारंभ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

Portion क्लास का नया उदाहरण प्रारंभ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है जिसमें स्पष्ट रूप से सेट किए गए फ़ॉर्मेटिंग गुण होते हैं जो पाठ भाग के हैं और कोई विरासत लागू नहीं हुई है। केवल-पढ़ने योग्य [IPortionFormat](../../com.aspose.slides/iportionformat)।

--------------------

फ़ॉर्मेटिंग ऑब्जेक्ट में केवल वर्तमान भाग के लिए परिभाषित फ़ॉर्मेटिंग पैरामीटर होते हैं, विरासत में प्राप्त डेटा लागू नहीं किया जाता है।

विरासत वाले सहित प्रभावी मान प्राप्त करने के लिए [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) मेथड का उपयोग करें।

**वापसी:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```

एक भाग का सरल टेक्स्ट प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String।

मान: टेक्स्ट।

**वापसी:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

एक भाग का सरल टेक्स्ट प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य String।

मान: टेक्स्ट।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

इस भाग का एक फ़ील्ड लौटाता है। केवल-पढ़ने योग्य [IField](../../com.aspose.slides/ifield)।

**वापसी:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

इस भाग को स्वचालित रूप से अद्यतन फ़ील्ड में परिवर्तित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

इस भाग को स्वचालित रूप से अद्यतन फ़ील्ड में परिवर्तित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| internalString | java.lang.String | FieldType का आंतरिक नाम। |

### removeField() {#removeField--}
```
public final void removeField()
```

इस फ़ील्ड भाग को साधारण भाग में परिवर्तित करता है।

### getRect() {#getRect--}
```
public final RectF getRect()
```

भाग को सीमित करने वाले आयत के निर्देशांक प्राप्त करता है। आयत में भाग के सभी टेक्स्ट पंक्तियाँ शामिल हैं, खाली पंक्तियों सहित।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try
>  {
>  	ISlide slide = pres.getSlides().get_Item(0);
>  	IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 200, 50);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().clear();
>  	Portion portion0 = new Portion("Some text");
>  	Portion portion1 = new Portion("GetRect text");
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion0);
>  	shape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion1);
>  	android.graphics.RectF rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public final PointF getCoordinates()
```

भाग की शुरुआत के निर्देशांक प्राप्त करता है। बिंदु का X निर्देशांक भाग की शुरुआत को दर्शाता है, जिसमें पहला अक्षर और बाएँ साइड बियरिंग शामिल है। Y निर्देशांक में शीर्ष साइड बियरिंग शामिल है।

**वापसी:**
android.graphics.PointF
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

पाठ की मातृ स्लाइड लौटाता है। केवल-पढ़ने योग्य [BaseSlide](../../com.aspose.slides/baseslide)।

**वापसी:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

पाठ की मातृ प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**वापसी:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**वापसी:**
com.aspose.slides.IDOMObject