---
title: Paragraph
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: Metin paragrafını temsil eder.
type: docs
url: /tr/com.aspose.slides/paragraph/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

Bir metin paragrafını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Paragraph()](#Paragraph--) | Varsayılan özelliklerle bir Paragraph nesnesinin yeni bir örneğini başlatır. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Bir Paragraph nesnesinin yeni bir örneğini başlatan kopya yapıcı. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPortions()](#getPortions--) | Metin bölümlerinin koleksiyonunu döndürür. |
| [getParagraphFormat()](#getParagraphFormat--) | Bu paragraf için biçimlendirme nesnesini döndürür. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Aynı biçimlendirmeye sahip çalışmaları birleştirir. |
| [getText()](#getText--) | Bir paragrafın düz metnini alır veya ayarlar. |
| [setText(String value)](#setText-java.lang.String-) | Bir paragrafın düz metnini alır veya ayarlar. |
| [getRect()](#getRect--) | Paragrafı sınırlayan dikdörtgenin koordinatlarını al. |
| [getLinesCount()](#getLinesCount--) | Bir paragraftaki satır sayısını al. |
| [getImage()](#getImage--) | Paragrafın bir görüntüsünü döndürür. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Belirtilen ölçekle paragrafın bir görüntüsünü döndürür. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Sonuna bir başka bölüm eklendiğinde kullanılacak bölüm özelliklerini belirtir. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Sonuna bir başka bölüm eklendiğinde kullanılacak bölüm özelliklerini belirtir. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Bir paragrafın üst slaytını döndürür. |
| [getPresentation()](#getPresentation--) | Bir paragrafın üst sunumunu döndürür. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```

Varsayılan özelliklerle bir Paragraph nesnesinin yeni bir örneğini başlatır.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

Bir Paragraph nesnesinin yeni bir örneğini başlatan kopya yapıcı.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

Salt okunur [IPortionCollection](../../com.aspose.slides/iportioncollection). Metin bölümlerinin koleksiyonunu döndürür.

**Döndürür:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

Salt okunur [IParagraphFormat](../../com.aspose.slides/iparagraphformat). Bu paragraf için biçimlendirme nesnesini döndürür.

--------------------

Biçimlendirme nesnesi yalnızca geçerli paragraf için tanımlanan biçimlendirme parametrelerini içerir, kalıtılan veriler uygulanmaz.

Kalıtılanları da içeren etkili değerleri almak için [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective) yöntemini kullanın.

**Döndürür:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Aynı biçimlendirmeye sahip çalışmaları birleştirir.

### getText() {#getText--}
```
public final String getText()
```

Okuma/Yazma String. Bir paragrafın düz metnini alır veya ayarlar.

Değer: Metin.

**Döndürür:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Okuma/Yazma String. Bir paragrafın düz metnini alır veya ayarlar.

Değer: Metin.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```

Paragrafı sınırlayan dikdörtgenin koordinatlarını al. Dikdörtgen, paragraftaki tüm metin satırlarını, boş satırlar dahil, içerir.

**Döndürür:**
android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
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

**Döndürür:**
int - Paragraftaki satır sayısı
### getImage() {#getImage--}
```
public final IImage getImage()
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

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Renderlanan paragrafı içeren bir görüntü; paragraf üst koleksiyonunda bulunamazsa, geçerli bir renderleme sınırı yoksa veya görüntü renderlenirken bir hata oluşursa null döndürür.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
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

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Renderlanan paragrafı içeren bir görüntü; paragraf üst koleksiyonunda bulunamazsa, geçerli bir renderleme sınırı yoksa veya görüntü renderlenirken bir hata oluşursa null döndürür.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

Sonuna bir başka bölüm eklendiğinde kullanılacak bölüm özelliklerini belirtir.

**Döndürür:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

Sonuna bir başka bölüm eklendiğinde kullanılacak bölüm özelliklerini belirtir.

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

Bir paragrafın üst slaytını döndürür. Salt okunur [BaseSlide](../../com.aspose.slides/baseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Bir paragrafın üst sunumunu döndürür. Salt okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)