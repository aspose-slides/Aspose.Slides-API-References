---
title: IParagraph
second_title: Aspose.Slides for Java API Referansı
description: Metnin bir paragrafını temsil eder.
type: docs
url: /tr/com.aspose.slides/iparagraph/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Metnin bir paragrafını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPortions()](#getPortions--) | Metin bölümlerinin koleksiyonunu döndürür. |
| [getParagraphFormat()](#getParagraphFormat--) | Bu paragraf için biçimlendirme nesnesini döndürür. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Aynı biçimlendirmeye sahip çalıştırmaları birleştirir. |
| [getText()](#getText--) | Paragrafın düz metnini alır veya ayarlar. |
| [setText(String value)](#setText-java.lang.String-) | Paragrafın düz metnini alır veya ayarlar. |
| [getRect()](#getRect--) | Paragrafı sınırlayan dikdörtgenin koordinatlarını al. |
| [getLinesCount()](#getLinesCount--) | Paragraftaki satır sayısını al. |
| [getImage()](#getImage--) | Paragrafın bir görüntüsünü döndürür. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Belirtilen ölçekle paragrafın bir görüntüsünü döndürür. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Sonuncusunun ardından başka bir parça eklenirse kullanılacak parça özelliklerini belirtir. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Sonuncusunun ardından başka bir parça eklenirse kullanılacak parça özelliklerini belirtir. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

Metin bölümlerinin koleksiyonunu döndürür. Salt okunur [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Döndürür:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

Bu paragraf için biçimlendirme nesnesini döndürür. Salt okunur [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Döndürür:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Aynı biçimlendirmeye sahip çalıştırmaları birleştirir.

### getText() {#getText--}
```
public abstract String getText()
```

Paragrafın düz metnini alır veya ayarlar. Okunur/Yazılabilir String.

Değer: Metin.

**Döndürür:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Paragrafın düz metnini alır veya ayarlar. Okunur/Yazılabilir String.

Değer: Metin.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

Paragrafı sınırlayan dikdörtgenin koordinatlarını al. Dikdörtgen, paragraftaki tüm metin satırlarını, boş satırları da içerecek şekilde kapsar.

**Döndürür:**
java.awt.geom.Rectangle2D.Float - Paragrafı sınırlayan dikdörtgen java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
```

Paragraftaki satır sayısını al.

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

**Döndürür:** int - Paragraftaki satır sayısı
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Paragrafın bir görüntüsünü döndürür.

--------------------

> ```
> The following example shows how to render a paragraph as an image:
>   
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(
>          ShapeType.Rectangle, 50, 50, 150, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      paragraph.setText("Aspose Paragraph GetImage() Example");
>      IImage paragraphImage = paragraph.getImage();
>      try {
>          paragraphImage.save("paragraph.png");
>      } finally {
>          if (paragraphImage != null) paragraphImage.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:** [IImage](../../com.aspose.slides/iimage) - Render edilmiş paragrafı içeren bir görüntü, veya paragraf üst koleksiyonunda bulunamıyorsa, geçerli bir render sınırı yoksa veya görüntü render edilirken bir hata oluşursa null.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

Belirtilen ölçekle paragrafın bir görüntüsünü döndürür.

--------------------

> ```
> The following example shows how to render each text box paragraph on a slide as an image with custom scaling:
>   
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      int shapeIndex = 0;
>      for (IShape shape : slide.getShapes())
>      {
>          shapeIndex++;
>          if (shape instanceof IAutoShape) {
>              IAutoShape autoShape = (IAutoShape)shape;
>              int paragraphIndex = 0;
>              for (IParagraph paragraph : autoShape.getTextFrame().getParagraphs())
>              {
>                  paragraphIndex++;
>                  IImage paragraphImage = paragraph.getImage(2f, 2f);
>                  try {
>                      if (paragraphImage != null)
>                          paragraphImage.save("shape"+shapeIndex+"_paragraph"+paragraphIndex+".png");
> 
>                  } finally {
>                      if (paragraphImage != null) paragraphImage.dispose();
>                  }
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scaleX | float | Paragraf görüntüsüne uygulanan yatay ölçek faktörü. |
| scaleY | float | Paragraf görüntüsüne uygulanan dikey ölçek faktörü. |

**Döndürür:** [IImage](../../com.aspose.slides/iimage) - Render edilmiş paragrafı içeren bir görüntü, veya paragraf üst koleksiyonunda bulunamıyorsa, geçerli bir render sınırı yoksa veya görüntü render edilirken bir hata oluşursa null.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

Sonuncusunun ardından başka bir parça eklenirse kullanılacak parça özelliklerini belirtir.

**Döndürür:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

Sonuncusunun ardından başka bir parça eklenirse kullanılacak parça özelliklerini belirtir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |