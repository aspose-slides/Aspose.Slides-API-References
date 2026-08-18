---
title: Portion
second_title: Aspose.Slides for Java API Referansı
description: Bir metin paragrafı içindeki bir metin bölümünü temsil eder.
type: docs
url: /tr/com.aspose.slides/portion/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

Bir metin paragrafı içinde bir metin bölümü temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Portion()](#Portion--) | Portion sınıfının yeni bir örneğini oluşturur. |
| [Portion(String str)](#Portion-java.lang.String-) | Portion sınıfının yeni bir örneğini oluşturur. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Portion sınıfının yeni bir örneğini oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Kalıtım uygulanmadan, metin bölümünün açıkça ayarlanmış biçimlendirme özelliklerini içeren bir biçimlendirme nesnesi döndürür. |
| [getText()](#getText--) | Bir bölümün düz metnini alır veya ayarlar. |
| [setText(String value)](#setText-java.lang.String-) | Bir bölümün düz metnini alır veya ayarlar. |
| [getField()](#getField--) | Bu bölümün bir alanını döndürür. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Bu bölümü otomatik olarak güncellenen alana dönüştürür. |
| [addField(String internalString)](#addField-java.lang.String-) | Bu bölümü otomatik olarak güncellenen alana dönüştürür. |
| [removeField()](#removeField--) | Bu alan bölümünü basit bölüme dönüştürür. |
| [getRect()](#getRect--) | Bölümü sınırlayan dikdörtgenin koordinatlarını al. |
| [getCoordinates()](#getCoordinates--) | Bölümün başlangıç koordinatlarını al. |
| [getSlide()](#getSlide--) | Metnin üst slaytını döndürür. |
| [getPresentation()](#getPresentation--) | Metnin üst sunumunu döndürür. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```

Portion sınıfının yeni bir örneğini oluşturur.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

Portion sınıfının yeni bir örneğini oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

Portion sınıfının yeni bir örneğini oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

Kalıtım uygulanmadan, metin bölümünün açıkça ayarlanmış biçimlendirme özelliklerini içeren bir biçimlendirme nesnesi döndürür. Yalnızca okuma [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Biçimlendirme nesnesi yalnızca geçerli bölüm için tanımlanan biçimlendirme parametrelerini içerir, kalıtım verileri uygulanmaz.

Kalıtım dahil etkili değerleri almak için [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) yöntemini kullanın.

**Döndürür:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```

Bir bölümün düz metnini alır veya ayarlar. Okuma/yazma String.

Değer: Metin.

**Döndürür:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Bir bölümün düz metnini alır veya ayarlar. Okuma/yazma String.

Değer: Metin.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

Bu bölümün bir alanını döndürür. Yalnızca okuma [IField](../../com.aspose.slides/ifield).

**Döndürür:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public final void addField(IFieldType fieldType)
```

Bu bölümü otomatik olarak güncellenen alana dönüştürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### addField(String internalString) {#addField-java.lang.String-}
```
public final void addField(String internalString)
```

Bu bölümü otomatik olarak güncellenen alana dönüştürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| internalString | java.lang.String | FieldType'ın iç adı. |

### removeField() {#removeField--}
```
public final void removeField()
```

Bu alan bölümünü basit bölüme dönüştürür.

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

Bölümü sınırlayan dikdörtgenin koordinatlarını al. Dikdörtgen, bölüme ait tüm metin satırlarını, boş olanları da kapsar.

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


**Döndürür:**
java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public final Point2D.Float getCoordinates()
```

Bölümün başlangıç koordinatlarını al. Noktanın X koordinatı, bölümün ilk karakterinden başlayarak sol taraftan taşıma dahil olmak üzere başlangıcı temsil eder. Y koordinatı üst taraftan taşıma içerir.

**Döndürür:**
java.awt.geom.Point2D.Float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Metnin üst slaytını döndürür. Yalnızca okuma [BaseSlide](../../com.aspose.slides/baseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Metnin üst sunumunu döndürür. Yalnızca okuma [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca okuma IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject