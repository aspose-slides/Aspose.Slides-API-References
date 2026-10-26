---
title: Portion
second_title: Aspose.Slides for Java API संदर्भ
description: टेक्स्ट पैराग्राफ़ के भीतर टेक्स्ट के एक भाग का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/portion/
---
**Inheritance:**  
विरासत:

**All Implemented Interfaces:**  
सभी लागू इंटरफ़ेस:
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

टेक्स्ट पैराग्राफ़ के भीतर टेक्स्ट के एक भाग का प्रतिनिधित्व करता है।

## Constructors

| Constructor | Description |
| --- | --- |
| [Portion()](#Portion--) | Portion क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Portion(String str)](#Portion-java.lang.String-) | Portion क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Portion क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## Methods

| Method | Description |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | फ़ॉर्मेटिंग वस्तु लौटाता है जिसमें टेक्स्ट भाग की स्पष्ट रूप से सेट फ़ॉर्मेटिंग प्रॉपर्टी शामिल हैं, बिना विरासत लागू किए। |
| [getText()](#getText--) | एक भाग के सरल टेक्स्ट को प्राप्त या सेट करता है। |
| [setText(String value)](#setText-java.lang.String-) | एक भाग के सरल टेक्स्ट को प्राप्त या सेट करता है। |
| [getField()](#getField--) | इस भाग का फ़ील्ड लौटाता है। |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | इस भाग को स्वचालित रूप से अपडेट किए गए फ़ील्ड में बदलता है। |
| [addField(String internalString)](#addField-java.lang.String-) | इस भाग को स्वचालित रूप से अपडेट किए गए फ़ील्ड में बदलता है। |
| [removeField()](#removeField--) | इस फ़ील्ड भाग को साधारण भाग में बदलता है। |
| [getRect()](#getRect--) | उस आयत के निर्देशांक प्राप्त करें जो भाग को घेरता है। |
| [getCoordinates()](#getCoordinates--) | भाग की शुरुआत के निर्देशांक प्राप्त करें। |
| [getSlide()](#getSlide--) | टेक्स्ट की पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | टेक्स्ट की पैरेंट प्रेजेंटेशन लौटाता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Portion() {#Portion--}
```
public Portion()
```

Portion क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

Portion क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

Portion क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

फ़ॉर्मेटिंग वस्तु लौटाता है जिसमें टेक्स्ट भाग की स्पष्ट रूप से सेट फ़ॉर्मेटिंग प्रॉपर्टी शामिल हैं, बिना विरासत लागू किए। केवल-पढ़ने योग्य [IPortionFormat](../../com.aspose.slides/iportionformat)।

फ़ॉर्मेटिंग ऑब्जेक्ट में वर्तमान भाग के लिए केवल परिभाषित फ़ॉर्मेटिंग पैरामीटर होते हैं, विरासत डेटा लागू नहीं होता।

विरासत सहित प्रभावी मान प्राप्त करने के लिए [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) मेथड का उपयोग करें।

**Returns:**  
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getText() {#getText--}
```
public final String getText()
```

एक भाग के सरल टेक्स्ट को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य स्ट्रिंग।

मान: टेक्स्ट।

**Returns:**  
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

एक भाग के सरल टेक्स्ट को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य स्ट्रिंग।

मान: टेक्स्ट।

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

इस भाग का फ़ील्ड लौटाता है। केवल-पढ़ने योग्य [IField](../../com.aspose.slides/ifield)।

**Returns:**  
[IField](../../com.aspose.slides/ifield)

### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

इस भाग को स्वचालित रूप से अपडेट किए गए फ़ील्ड में बदलता है।

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

इस भाग को स्वचालित रूप से अपडेट किए गए फ़ील्ड में बदलता है।

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| internalString | java.lang.String | फ़ील्डटाइप का आंतरिक नाम। |

### removeField() {#removeField--}
```
public final void removeField()
```

इस फ़ील्ड भाग को साधारण भाग में बदलता है।

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

उस आयत के निर्देशांक प्राप्त करें जो भाग को घेरता है। आयत में भाग की सभी टेक्स्ट लाइनों, खाली लाइनों सहित, शामिल हैं।

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
>  	Rectangle2D.Float rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**Returns:**  
java.awt.geom.Rectangle2D.Float

### getCoordinates() {#getCoordinates--}
```
public final Point2D.Float getCoordinates()
```

भाग की शुरुआत के निर्देशांक प्राप्त करें। बिंदु का X निर्देशांक भाग की शुरुआत को पहले अक्षर से बाएँ साइड बियरिंग सहित दर्शाता है। Y निर्देशांक शीर्ष साइड बियरिंग शामिल करता है।

**Returns:**  
java.awt.geom.Point2D.Float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

टेक्स्ट की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [BaseSlide](../../com.aspose.slides/baseslide)।

**Returns:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

टेक्स्ट की पैरेंट प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**Returns:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**Returns:**  
com.aspose.slides.IDOMObject