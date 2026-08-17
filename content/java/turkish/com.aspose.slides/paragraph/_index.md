---
title: Paragraph
second_title: Aspose.Slides için Java API Referansı
description: Metin paragrafını temsil eder.
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

Metin paragrafını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Paragraph()](#Paragraph--) | Paragraph sınıfının varsayılan özelliklerle yeni bir örneğini başlatır. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Paragraph sınıfının yeni bir örneğini başlatan kopya yapıcı. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getPortions()](#getPortions--) | Metin bölümlerinin koleksiyonunu döndürür. |
| [getParagraphFormat()](#getParagraphFormat--) | Bu paragraf için biçimlendirme nesnesini döndürür. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Aynı biçimlendirmeye sahip çalıştırmaları birleştirir. |
| [getText()](#getText--) | Bir paragrafın düz metnini alır veya ayarlar. |
| [setText(String value)](#setText-java.lang.String-) | Bir paragrafın düz metnini alır veya ayarlar. |
| [getRect()](#getRect--) | Paragrafı sınırlayan dikdörtgenin koordinatlarını al. |
| [getLinesCount()](#getLinesCount--) | Bir paragraftaki satır sayısını al. |
| [getImage()](#getImage--) | Paragrafın bir görüntüsünü döndürür. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Belirtilen ölçekle paragrafın bir görüntüsünü döndürür. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Son bölüme bir başka bölüm eklendiğinde kullanılacak bölüm özelliklerini belirtir. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Son bölüme bir başka bölüm eklendiğinde kullanılacak bölüm özelliklerini belirtir. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Bir paragrafın ebeveyn slaytını döndürür. |
| [getPresentation()](#getPresentation--) | Bir paragrafın ebeveyn sunumunu döndürür. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```

Paragraph sınıfının varsayılan özelliklerle yeni bir örneğini başlatır.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

Kopya yapıcı, Paragraph sınıfının yeni bir örneğini başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

Metin bölümlerinin koleksiyonunu döndürür. Salt okunur [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Döndürür:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

Bu paragraf için biçimlendirme nesnesini döndürür. Salt okunur [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

Biçimlendirme nesnesi yalnızca geçerli paragraf için tanımlanan biçimlendirme parametrelerini içerir; kalıtılmış veriler uygulanmaz.

Kalıtılmış değerler dahil olmak üzere etkili değerleri almak için [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective) metodunu kullanın.

**Döndürür:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Aynı biçimlendirmeye sahip çalıştırmaları birleştirir.

### getText() {#getText--}
```
public final String getText()
```

Bir paragrafın düz metnini alır veya ayarlar. Okunur/yazılabilir String.

Değer: Metin.

**Döndürür:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Bir paragrafın düz metnini alır veya ayarlar. Okunur/yazılabilir String.

Değer: Metin.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

Paragrafı sınırlayan dikdörtgenin koordinatlarını al. Dikdörtgen, paragraftaki tüm metin satırlarını, boş satırları da dahil, içerir.

**Döndürür:**
java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

Bir paragraftaki satır sayısını al.

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
int - Bir paragraftaki satır sayısı
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
[IImage](../../com.aspose.slides/iimage) - Render edilmiş paragrafı içeren bir görüntü, ya da paragraf ebeveyn koleksiyonunda bulunamazsa, geçerli bir render sınırı yoksa veya görüntü oluşturulurken bir hata oluşursa null.
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
[IImage](../../com.aspose.slides/iimage) - Render edilmiş paragrafı içeren bir görüntü, ya da paragraf ebeveyn koleksiyonunda bulunamazsa, geçerli bir render sınırı yoksa veya görüntü oluşturulurken bir hata oluşursa null.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

Son bölüme bir başka bölüm eklendiğinde kullanılacak bölüm özelliklerini belirtir.

**Döndürür:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

Son bölüme bir başka bölüm eklendiğinde kullanılacak bölüm özelliklerini belirtir.

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

Bir paragrafın ebeveyn slaytını döndürür. Salt okunur [BaseSlide](../../com.aspose.slides/baseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Bir paragrafın ebeveyn sunumunu döndürür. Salt okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)