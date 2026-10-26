---
title: IPortion
second_title: Aspose.Slides for Android के लिए जावा API संदर्भ
description: एक टेक्स्ट पैराग्राफ के भीतर टेक्स्ट के भाग का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iportion/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

एक टेक्स्ट पैराग्राफ के भीतर टेक्स्ट का एक भाग दर्शाता है।
## Methods

| Method | Description |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है जिसमें टेक्स्ट भाग की स्पष्ट रूप से सेट फ़ॉर्मेटिंग प्रॉपर्टीज़ होती हैं और कोई विरासत लागू नहीं होती। |
| [getText()](#getText--) | एक भाग का साधारण टेक्स्ट प्राप्त करता है या सेट करता है। |
| [setText(String value)](#setText-java.lang.String-) | एक भाग का साधारण टेक्स्ट प्राप्त करता है या सेट करता है। |
| [getField()](#getField--) | इस भाग का फ़ील्ड लौटाता है। |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | इस भाग को स्वचालित रूप से अपडेट किए गए फ़ील्ड में बदलता है। |
| [addField(String internalString)](#addField-java.lang.String-) | इस भाग को स्वचालित रूप से अपडेट किए गए फ़ील्ड में बदलता है। |
| [removeField()](#removeField--) | इस फ़ील्ड भाग को साधारण भाग में बदलता है। |
| [getRect()](#getRect--) | भाग को घेरने वाले आयत के निर्देशांक प्राप्त करें। |
| [getCoordinates()](#getCoordinates--) | भाग की शुरुआत के निर्देशांक प्राप्त करें। |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है जिसमें टेक्स्ट भाग की स्पष्ट रूप से सेट फ़ॉर्मेटिंग प्रॉपर्टीज़ होती हैं और कोई विरासत लागू नहीं होती। केवल-पढ़ने योग्य [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

फ़ॉर्मेटिंग ऑब्जेक्ट केवल वर्तमान भाग के लिए परिभाषित फ़ॉर्मेटिंग पैरामीटर रखता है, विरासत डेटा लागू नहीं होता।

विरासत वाले मानों सहित प्रभावी मान प्राप्त करने के लिए [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) मेथड का उपयोग करें।

**रिटर्न:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```

एक भाग का साधारण टेक्स्ट प्राप्त करता है या सेट करता है। पढ़ें/लिखें स्ट्रिंग।

मान: टेक्स्ट।

**रिटर्न:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

एक भाग का साधारण टेक्स्ट प्राप्त करता है या सेट करता है। पढ़ें/लिखें स्ट्रिंग।

मान: टेक्स्ट।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getField() {#getField--}
```
public abstract IField getField()
```

इस भाग का फ़ील्ड लौटाता है। केवल-पढ़ने योग्य [IField](../../com.aspose.slides/ifield)।

**रिटर्न:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```

इस भाग को स्वचालित रूप से अपडेट किए गए फ़ील्ड में बदलता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | फ़ील्ड का प्रकार [IFieldType](../../com.aspose.slides/ifieldtype) |
### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```

इस भाग को स्वचालित रूप से अपडेट किए गए फ़ील्ड में बदलता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| internalString | java.lang.String | FieldTypeEx स्ट्रिंग का आंतरिक नाम |
### removeField() {#removeField--}
```
public abstract void removeField()
```

इस फ़ील्ड भाग को साधारण भाग में बदलता है।

### getRect() {#getRect--}
```
public abstract RectF getRect()
```

भाग को घेरने वाले आयत के निर्देशांक प्राप्त करें। आयत में भाग के सभी टेक्स्ट लाइन्स शामिल होते हैं, यहाँ तक कि खाली लाइन्स भी।

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


**रिटर्न:**
android.graphics.RectF - भाग को घेरने वाला आयत android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public abstract PointF getCoordinates()
```

भाग की शुरुआत के निर्देशांक प्राप्त करें। बिंदु का X निर्देशांक पहले चरित्र से शुरू होने वाले भाग को दर्शाता है जिसमें बाएँ ओर की बियरिंग शामिल है। Y निर्देशांक में शीर्ष बियरिंग शामिल है।

**रिटर्न:**
android.graphics.PointF - भाग की शुरुआत के निर्देशांक android.graphics.PointF