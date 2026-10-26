---
title: IPortion
second_title: Aspose.Slides for Java API संदर्भ
description: एक पाठ अनुच्छेद के भीतर पाठ के एक भाग का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iportion/
---
**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

एक पाठ अनुच्छेद के भीतर पाठ के भाग का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | भाग के उन फ़ॉर्मेटिंग गुणों को लौटाता है जो स्पष्ट रूप से सेट किए गए हैं और जिनमें कोई विरासत नहीं लगाई गई। |
| [getText()](#getText--) | एक भाग का साधारण पाठ प्राप्त करता है या सेट करता है। |
| [setText(String value)](#setText-java.lang.String-) | एक भाग का साधारण पाठ प्राप्त करता है या सेट करता है। |
| [getField()](#getField--) | इस भाग का फ़ील्ड लौटाता है। |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | इस भाग को स्वचालित रूप से अपडेट किए गए फ़ील्ड में परिवर्तित करता है। |
| [addField(String internalString)](#addField-java.lang.String-) | इस भाग को स्वचालित रूप से अपडेट किए गए फ़ील्ड में परिवर्तित करता है। |
| [removeField()](#removeField--) | इस फ़ील्ड भाग को साधारण भाग में परिवर्तित करता है। |
| [getRect()](#getRect--) | भाग को सीमित करने वाले आयत के निर्देशांक प्राप्त करें। |
| [getCoordinates()](#getCoordinates--) | भाग की शुरुआत के निर्देशांक प्राप्त करें। |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

एक फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है जो स्पष्ट रूप से सेट किए गए फ़ॉर्मेटिंग गुणों को शामिल करता है और जिसमें कोई विरासत लागू नहीं हुई है। केवल-पढ़ने-योग्य [IPortionFormat](../../com.aspose.slides/iportionformat)।

--------------------

फ़ॉर्मेटिंग ऑब्जेक्ट केवल वर्तमान भाग के लिए परिभाषित फ़ॉर्मेटिंग पैरामीटर शामिल करता है, विरासत में मिले डेटा लागू नहीं होते।

विरासत वाले मूल्यों सहित प्रभावी मान प्राप्त करने के लिए [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) विधि का प्रयोग करें।

**रिटर्न्स:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```

एक भाग का साधारण पाठ प्राप्त करता है या सेट करता है। पढ़ने/लिखने-योग्य String।

मान: पाठ।

**रिटर्न्स:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

एक भाग का साधारण पाठ प्राप्त करता है या सेट करता है। पढ़ने/लिखने-योग्य String।

मान: पाठ।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public abstract IField getField()
```

इस भाग का फ़ील्ड लौटाता है। केवल-पढ़ने-योग्य [IField](../../com.aspose.slides/ifield)।

**रिटर्न्स:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```

इस भाग को स्वचालित रूप से अपडेट किए गए फ़ील्ड में परिवर्तित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | फ़ील्ड प्रकार [IFieldType](../../com.aspose.slides/ifieldtype) |

### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```

इस भाग को स्वचालित रूप से अपडेट किए गए फ़ील्ड में परिवर्तित करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| internalString | java.lang.String | FieldTypeEx String का आंतरिक नाम |

### removeField() {#removeField--}
```
public abstract void removeField()
```

इस फ़ील्ड भाग को साधारण भाग में परिवर्तित करता है।

### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

भाग को सीमित करने वाले आयत के निर्देशांक प्राप्त करें। आयत में भाग की सभी पाठ पंक्तियाँ शामिल होती हैं, जिसमें खाली पंक्तियाँ भी होती हैं।

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
>  	Rectangle2D.Float rect = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न्स:**
java.awt.geom.Rectangle2D.Float - भाग को सीमित करने वाला आयत java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public abstract Point2D.Float getCoordinates()
```

भाग की शुरुआत के निर्देशांक प्राप्त करें। बिंदु का X निर्देशांक भाग की शुरुआत को प्रथम अक्षर से बाएँ साइड बियरिंग सहित दर्शाता है। Y निर्देशांक शीर्ष साइड बियरिंग को शामिल करता है।

**रिटर्न्स:**
java.awt.geom.Point2D.Float - भाग की शुरुआत के निर्देशांक java.awt.geom.Point2D.Float