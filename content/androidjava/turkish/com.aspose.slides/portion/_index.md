---
title: Portion
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bir metin paragrafı içindeki bir metin bölümünü temsil eder.
type: docs
url: /tr/com.aspose.slides/portion/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IPortion](../../com.aspose.slides/iportion), com.aspose.slides.IDOMObject
```
public class Portion implements IPortion, IDOMObject
```

Bir metin paragrafı içindeki bir metin bölümü temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Portion()](#Portion--) | Portion sınıfının yeni bir örneğini başlatır. |
| [Portion(String str)](#Portion-java.lang.String-) | Portion sınıfının yeni bir örneğini başlatır. |
| [Portion(Portion portion)](#Portion-com.aspose.slides.Portion-) | Portion sınıfının yeni bir örneğini başlatır. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getPortionFormat()](#getPortionFormat--) | Kalıtım uygulanmadan metin bölümünün açıkça ayarlanmış biçimlendirme özelliklerini içeren bir biçimlendirme nesnesi döndürür. |
| [getText()](#getText--) | Bir bölümün düz metnini alır veya ayarlar. |
| [setText(String value)](#setText-java.lang.String-) | Bir bölümün düz metnini alır veya ayarlar. |
| [getField()](#getField--) | Bu bölümün bir alanını döndürür. |
| [addField(IFieldType fieldType)](#addField-com.aspose.slides.IFieldType-) | Bu bölümü otomatik olarak güncellenen alana dönüştürür. |
| [addField(String internalString)](#addField-java.lang.String-) | Bu bölümü otomatik olarak güncellenen alana dönüştürür. |
| [removeField()](#removeField--) | Bu alan bölümünü basit bölüme dönüştürür. |
| [getRect()](#getRect--) | Bölümü sınırlayan dikdörtgenin koordinatlarını al. |
| [getCoordinates()](#getCoordinates--) | Bölümün başlangıç koordinatlarını al. |
| [getSlide()](#getSlide--) | Bir metnin üst slaytını döndürür. |
| [getPresentation()](#getPresentation--) | Bir metnin üst sunumunu döndürür. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Portion() {#Portion--}
```
public Portion()
```

Portion sınıfının yeni bir örneğini başlatır.

### Portion(String str) {#Portion-java.lang.String-}
```
public Portion(String str)
```

Portion sınıfının yeni bir örneğini başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | java.lang.String |  |

### Portion(Portion portion) {#Portion-com.aspose.slides.Portion-}
```
public Portion(Portion portion)
```

Portion sınıfının yeni bir örneğini başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) |  |

### getPortionFormat() {#getPortionFormat--}
```
public final IPortionFormat getPortionFormat()
```

Kalıtım uygulanmadan metin bölümünün açıkça ayarlanmış biçimlendirme özelliklerini içeren bir biçimlendirme nesnesi döndürür. Yalnızca okunur [IPortionFormat](../../com.aspose.slides/iportionformat).

--------------------

Biçimlendirme nesnesi yalnızca geçerli bölüm için tanımlanan biçimlendirme parametrelerini içerir, kalıtılan veri uygulanmaz.

Kalıtılan değerler dahil etkin değerleri almak için [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) yöntemini kullanın.

**Döndürür:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getText() {#getText--}
```
public final String getText()
```

Bir bölümün düz metnini alır veya ayarlar. Okunur/yazılır String.

Değer: Metin.

**Döndürür:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Bir bölümün düz metnini alır veya ayarlar. Okunur/yazılır String.

Değer: Metin.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getField() {#getField--}
```
public final IField getField()
```

Bu bölümün bir alanını döndürür. Yalnızca okunur [IField](../../com.aspose.slides/ifield).

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
| internalString | java.lang.String | AlanTürünün iç adı. |

### removeField() {#removeField--}
```
public final void removeField()
```

Bu alan bölümünü basit bölüme dönüştürür.

### getRect() {#getRect--}
```
public final RectF getRect()
```

Bölümü sınırlayan dikdörtgenin koordinatlarını al. Dikdörtgen, bölümdeki tüm metin satırlarını, boş satırlar dahil, içerir.

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
>  	android.graphics.RectF rect = shape.getTextFrame().getParagraphs().get_Item(1).getPortions().get_Item(1).getRect();
>  	...
>  } finally {
>  	if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
android.graphics.RectF
### getCoordinates() {#getCoordinates--}
```
public final PointF getCoordinates()
```

Bölümün başlangıç koordinatlarını al. Noktanın X koordinatı, sol kenar boşluğunu da içeren ilk karakterden itibaren bölümü başlatır. Y koordinatı üst kenar boşluğunu içerir.

**Döndürür:**
android.graphics.PointF
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Bir metnin üst slaytını döndürür. Yalnızca okunur [BaseSlide](../../com.aspose.slides/baseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Bir metnin üst sunumunu döndürür. Yalnızca okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject