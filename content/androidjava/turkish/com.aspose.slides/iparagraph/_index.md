---
title: IParagraph
second_title: Aspose.Slides for Android, Java API Referansı ile
description: Bir metnin paragrafını temsil eder.
type: docs
url: /tr/com.aspose.slides/iparagraph/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Bir metin paragrafını temsil eder.
## Yöntemler

| Method | Description |
| --- | --- |
| [getPortions()](#getPortions--) | Metin bölümlerinin koleksiyonunu döndürür. |
| [getParagraphFormat()](#getParagraphFormat--) | Bu paragraf için biçimlendirme nesnesini döndürür. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Aynı biçimlendirmeye sahip koşuları birleştirir. |
| [getText()](#getText--) | Bir paragrafın düz metnini alır veya ayarlar. |
| [setText(String value)](#setText-java.lang.String-) | Bir paragrafın düz metnini alır veya ayarlar. |
| [getRect()](#getRect--) | Paragrafı sınırlayan dikdörtgenin koordinatlarını alır. |
| [getLinesCount()](#getLinesCount--) | Bir paragraftaki satır sayısını alır. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Başka bir bölüm sonuncusunun ardından eklenecekse kullanılacak bölüm özelliklerini belirtir. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Başka bir bölüm sonuncusunun ardından eklenecekse kullanılacak bölüm özelliklerini belirtir. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

Metin bölümlerinin koleksiyonunu döndürür. Yalnızca okunabilir [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Döndürür:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

Bu paragraf için biçimlendirme nesnesini döndürür. Yalnızca okunabilir [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Döndürür:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Aynı biçimlendirmeye sahip koşuları birleştirir.

### getText() {#getText--}
```
public abstract String getText()
```

Bir paragrafın düz metnini alır veya ayarlar. Okuma/yazma String.

Değer: Metin.

**Döndürür:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Bir paragrafın düz metnini alır veya ayarlar. Okuma/yazma String.

Değer: Metin.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract RectF getRect()
```

Paragrafı sınırlayan dikdörtgenin koordinatlarını alır. Dikdörtgen, paragraftaki tüm metin satırlarını, boş satırları da dahil olmak üzere, içerir.

**Döndürür:**
android.graphics.RectF - Paragrafı sınırlayan dikdörtgen android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
```

Bir paragraftaki satır sayısını alır.

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
public abstract IPortionFormat getEndParagraphPortionFormat()
```

Başka bir bölüm sonuncusunun ardından eklenecekse kullanılacak bölüm özelliklerini belirtir.

**Döndürür:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

Başka bir bölüm sonuncusunun ardından eklenecekse kullanılacak bölüm özelliklerini belirtir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |