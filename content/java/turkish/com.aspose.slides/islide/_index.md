---
title: ISlide
second_title: Aspose.Slides for Java API Referansı
description: Bir sunumdaki slaytı temsil eder.
type: docs
url: /tr/com.aspose.slides/islide/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

Bir sunumdaki slaytı temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Slaytın HeaderFooter yöneticisini döndürür. |
| [getSlideNumber()](#getSlideNumber--) | Slayt numarasını döndürür. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Slayt numarasını döndürür. |
| [getHidden()](#getHidden--) | Belirtilen slaytın slayt gösterisi sırasında gizli olup olmadığını belirler. |
| [setHidden(boolean value)](#setHidden-boolean-) | Belirtilen slaytın slayt gösterisi sırasında gizli olup olmadığını belirler. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Özel ölçekleme ile bir görüntü nesnesi döndürür. |
| [getImage()](#getImage--) | Gerçek boyutun %20'si kadar bir Küçük Resim Görüntüsü nesnesi döndürür. |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Belirtilen boyutta bir görüntü nesnesi döndürür. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Belirtilen parametrelerle bir Küçük Resim tiff bit eşlem nesnesi döndürür. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Bir Küçük Resim Bit Eşlem nesnesi döndürür. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Özel ölçekleme ile bir Küçük Resim Bit Eşlem nesnesi döndürür. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Belirtilen boyutta bir Küçük Resim Bit Eşlem nesnesi döndürür. |
| [getLayoutSlide()](#getLayoutSlide--) | Geçerli slayt için düzen slaytını döndürür veya ayarlar. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Geçerli slayt için düzen slaytını döndürür veya ayarlar. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Not slaytına erişim, ekleme ve kaldırma izni verir. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Belirli bir yazar tarafından eklenen tüm slayt yorumlarını döndürür. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Slayt içeriğini bir SVG dosyası olarak kaydeder. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Slayt içeriğini bir SVG dosyası olarak kaydeder. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Slayt içeriğini bir EMF dosyası olarak kaydeder. |
| [remove()](#remove--) | Slaytı sunumdan kaldırır. |
| [reset()](#reset--) | LayoutSlide üzerinde prototipi olan her şeklin konumunu, boyutunu ve biçimlendirmesini sıfırlar. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

Slaytın HeaderFooter yöneticisini döndürür. Yalnızca okunur [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Döndürür:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

Slayt numarasını döndürür. [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) koleksiyonundaki slayt indeksi her zaman SlideNumber - 1’e eşittir. Okunur/yazılır int.

**Döndürür:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

Slayt numarasını döndürür. [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) koleksiyonundaki slayt indeksi her zaman SlideNumber - 1’e eşittir. Okunur/yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Belirtilen slaytın slayt gösterisi sırasında gizli olup olmadığını belirler. Okunur/yazılır boolean.

**Döndürür:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Belirtilen slaytın slayt gösterisi sırasında gizli olup olmadığını belirler. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

Özel ölçekleme ile bir görüntü nesnesi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scaleX | float | X ekseninde bu Küçük Resmi ölçeklemek için kullanılacak değer. |
| scaleY | float | Y ekseninde bu Küçük Resmi ölçeklemek için kullanılacak değer. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Gerçek boyutun %20'si kadar bir Küçük Resim Görüntüsü nesnesi döndürür.

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage
### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public abstract IImage getImage(Dimension imageSize)
```

Belirtilen boyutta bir görüntü nesnesi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageSize | java.awt.Dimension | Oluşturulacak görüntünün boyutu. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

Belirtilen parametrelerle bir Küçük Resim tiff bit eşlem nesnesi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff seçenekleri. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

Bir Küçük Resim Bit Eşlem nesnesi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | İşleme seçenekleri. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Özel ölçekleme ile bir Küçük Resim Bit Eşlem nesnesi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | İşleme seçenekleri. |
| scaleX | float | X ekseninde bu Küçük Resmi ölçeklemek için kullanılacak değer. |
| scaleY | float | Y ekseninde bu Küçük Resmi ölçeklemek için kullanılacak değer. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage getImage(IRenderingOptions options, Dimension imageSize)
```

Belirtilen boyutta bir Küçük Resim Bit Eşlem nesnesi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | İşleme seçenekleri. |
| imageSize | java.awt.Dimension | Oluşturulacak görüntünün boyutu. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

Geçerli slayt için düzen slaytını döndürür veya ayarlar. Okunur/yazılır [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

Geçerli slayt için düzen slaytını döndürür veya ayarlar. Okunur/yazılır [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

Not slaytına erişim, ekleme ve kaldırma izni verir. Yalnızca okunur [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Döndürür:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

Belirli bir yazar tarafından eklenen tüm slayt yorumlarını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Bulunacak yorumların yazarı veya tüm yorumları döndürmek için null. |

**Döndürür:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Slayt içeriğini bir SVG dosyası olarak kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Hedef akış |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Slayt içeriğini bir SVG dosyası olarak kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Hedef akış |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG oluşturma seçenekleri |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

Slayt içeriğini bir EMF dosyası olarak kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Hedef akış |
### remove() {#remove--}
```
public abstract void remove()
```

Slaytı sunumdan kaldırır.
### reset() {#reset--}
```
public abstract void reset()
```

LayoutSlide üzerinde prototipi olan her şeklin konumunu, boyutunu ve biçimlendirmesini sıfırlar.