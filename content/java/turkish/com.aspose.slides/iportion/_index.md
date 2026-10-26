---
title: IPortion
second_title: Aspose.Slides için Java API Referansı
description: Bir metin paragrafı içinde bir metin bölümünü temsil eder.
type: docs
url: /tr/com.aspose.slides/iportion/
---
**Tüm Gerçekleştirilmiş Arabirimler:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IPortion extends ISlideComponent
```

Bir metin paragrafı içinde bir metin bölümü temsil eder.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Kalıtım uygulanmadan metin bölümünün açıkça ayarlanmış biçimlendirme özelliklerini içeren biçimlendirme nesnesini döndürür. |
| [getText()](#getText--) | Bir bölümün düz metnini alır veya ayarlar. |
| [setText(String value)](#setText-java.lang.String-) | Bir bölümün düz metnini alır veya ayarlar. |
| [getField()](#getField--) | Bu bölümün bir alanını döndürür. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Bu bölümü otomatik olarak güncellenen alana dönüştürür. |
| [addField(String internalString)](#addField-java.lang.String-) | Bu bölümü otomatik olarak güncellenen alana dönüştürür. |
| [removeField()](#removeField--) | Bu alan bölümünü basit bölüme dönüştürür. |
| [getRect()](#getRect--) | Bölümü sınırlayan dikdörtgenin koordinatlarını alır. |
| [getCoordinates()](#getCoordinates--) | Bölümün başlangıcının koordinatlarını alır. |
### getPortionFormat() {#getPortionFormat--}
```
public abstract IPortionFormat getPortionFormat()
```

Kalıtım uygulanmadan metin bölümünün açıkça ayarlanmış biçimlendirme özelliklerini içeren biçimlendirme nesnesini döndürür. Salt okunur [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Biçimlendirme nesnesi yalnızca geçerli bölüm için tanımlanan biçimlendirme parametrelerini içerir, kalıtılan veriler uygulanmaz.

Kalıtılan değerler dahil olmak üzere etkili değerleri almak için [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) yöntemini kullanın.

**Döndürür:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public abstract String getText()
```

Bir bölümün düz metnini alır veya ayarlar. Okunur/Yazılabilir String.

Değer: Metin.

**Döndürür:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Bir bölümün düz metnini alır veya ayarlar. Okunur/Yazılabilir String.

Değer: Metin.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public abstract IField getField()
```

Bu bölümün bir alanını döndürür. Salt okunur [IField](../../com.aspose.slides/ifield).

**Döndürür:**
[IField](../../com.aspose.slides/ifield)
### addField(IFieldType fieldType) {#addField-com.aspose.slides.IFieldType-}
```
public abstract void addField(IFieldType fieldType)
```

Bu bölümü otomatik olarak güncellenen alana dönüştürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldType | [IFieldType](../../com.aspose.slides/ifieldtype) | Alan türü [IFieldType](../../com.aspose.slides/ifieldtype) |

### addField(String internalString) {#addField-java.lang.String-}
```
public abstract void addField(String internalString)
```

Bu bölümü otomatik olarak güncellenen alana dönüştürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| internalString | java.lang.String | FieldTypeEx String'in iç adı |

### removeField() {#removeField--}
```
public abstract void removeField()
```

Bu alan bölümünü basit bölüme dönüştürür.

### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

Bölümü sınırlayan dikdörtgenin koordinatlarını alır. Dikdörtgen, bölümdeki tüm metin satırlarını, boş satırları da dahil ederek içerir.

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
java.awt.geom.Rectangle2D.Float - Bölümü sınırlayan dikdörtgen java.awt.geom.Rectangle2D.Float
### getCoordinates() {#getCoordinates--}
```
public abstract Point2D.Float getCoordinates()
```

Bölümün başlangıcının koordinatlarını alır. Noktanın X koordinatı, soldan kenar boşluğunu da içerecek şekilde ilk karakterden itibaren bölümün başlangıcını temsil eder. Y koordinatı üst kenar boşluğunu içerir.

**Döndürür:**
java.awt.geom.Point2D.Float - Bölümün başlangıcının koordinatları java.awt.geom.Point2D.Float