---
title: Paragraph
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bir metin paragrafını temsil eder.
type: docs
url: /tr/com.aspose.slides/paragraph/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

Bir metin paragrafını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Paragraph()](#Paragraph--) | Paragraph sınıfının varsayılan özelliklerle yeni bir örneğini başlatır. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Paragraf sınıfının yeni bir örneğini başlatan kopya yapıcı. |

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getPortions()](#getPortions--) | Metin parçalarının koleksiyonunu döndürür. |
| [getParagraphFormat()](#getParagraphFormat--) | Bu paragraf için biçimlendirme nesnesini döndürür. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Aynı biçimlendirmeye sahip koşu parçalarını birleştirir. |
| [getText()](#getText--) | Bir paragrafın düz metnini alır veya ayarlar. |
| [setText(String value)](#setText-java.lang.String-) | Bir paragrafın düz metnini alır veya ayarlar. |
| [getRect()](#getRect--) | Paragrafı sınırlayan dikdörtgenin koordinatlarını alır. |
| [getLinesCount()](#getLinesCount--) | Paragraftaki satır sayısını alır. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Son parçadan sonra başka bir parça eklendiğinde kullanılacak parça özelliklerini belirtir. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Son parçadan sonra başka bir parça eklendiğinde kullanılacak parça özelliklerini belirtir. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Paragrafın üst slaytını döndürür. |
| [getPresentation()](#getPresentation--) | Paragrafın üst sunumunu döndürür. |

### Paragraph() {#Paragraph--}
```
public Paragraph()
```

Paragraph sınıfının varsayılan özelliklerle yeni bir örneğini başlatır.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

Paragraf sınıfının yeni bir örneğini başlatan kopya yapıcı.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

Metin parçalarının koleksiyonunu döndürür. Salt okunur [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Döndürür:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)

### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

Bu paragraf için biçimlendirme nesnesini döndürür. Salt okunur [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

Biçimlendirme nesnesi yalnızca mevcut paragraf için tanımlanan biçimlendirme parametrelerini içerir, kalıtılmış veriler uygulanmaz.

Kalıtılmış değerler dahil olmak üzere etkili değerleri almak için [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective) metodunu kullanın.

**Döndürür:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Aynı biçimlendirmeye sahip koşu parçalarını birleştirir.

### getText() {#getText--}
```
public final String getText()
```

Bir paragrafın düz metnini alır veya ayarlar. Okunur/yazılır String.

Değer: Metin.

**Döndürür:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Bir paragrafın düz metnini alır veya ayarlar. Okunur/yazılır String.

Değer: Metin.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```

Paragrafı sınırlayan dikdörtgenin koordinatlarını alır. Dikdörtgen, paragraftaki tüm metin satırlarını, boş satırlar dahil, içerir.

**Döndürür:**
android.graphics.RectF

### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

Paragraftaki satır sayısını alır.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
int - Paragraftaki satır sayısı

### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

Son parçadan sonra başka bir parça eklendiğinde kullanılacak parça özelliklerini belirtir.

**Döndürür:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

Son parçadan sonra başka bir parça eklendiğinde kullanılacak parça özelliklerini belirtir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Paragrafın üst slaytını döndürür. Salt okunur [BaseSlide](../../com.aspose.slides/baseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Paragrafın üst sunumunu döndürür. Salt okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)