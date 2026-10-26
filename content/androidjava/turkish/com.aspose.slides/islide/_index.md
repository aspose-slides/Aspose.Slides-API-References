---
title: ISlide
second_title: Java API Referansı ile Android için Aspose.Slides
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
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Slaytın HeaderFooter yöneticisini döndürür. |
| [getSlideNumber()](#getSlideNumber--) | Slaytın numarasını döndürür. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Slaytın numarasını döndürür. |
| [getHidden()](#getHidden--) | Belirtilen slaytın slayt gösterimi sırasında gizlenip gizlenmediğini belirler. |
| [setHidden(boolean value)](#setHidden-boolean-) | Belirtilen slaytın slayt gösterimi sırasında gizlenip gizlenmediğini belirler. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Özel ölçekleme ile bir görüntü nesnesi döndürür. |
| [getImage()](#getImage--) | Gerçek boyutun %20'si kadar bir Küçük Resim nesnesi döndürür. |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Belirtilen boyutta bir görüntü nesnesi döndürür. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Belirtilen parametrelerle bir Küçük Resim tiff bitmap nesnesi döndürür. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Küçük Resim Bitmap nesnesi döndürür. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Özel ölçekleme ile bir Küçük Resim Bitmap nesnesi döndürür. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Belirtilen boyutta bir Küçük Resim Bitmap nesnesi döndürür. |
| [getLayoutSlide()](#getLayoutSlide--) | Mevcut slayt için düzen slaytını döndürür veya ayarlar. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Mevcut slayt için düzen slaytını döndürür veya ayarlar. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Not slaytına erişim, ekleme ve kaldırma imkâni sağlar. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Belirli bir yazar tarafından eklenen tüm slayt yorumlarını döndürür. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Slayt içeriğini bir SVG dosyası olarak kaydeder. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Slayt içeriğini bir SVG dosyası olarak kaydeder. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Slayt içeriğini bir EMF dosyası olarak kaydeder. |
| [remove()](#remove--) | Slaytı sunumdan kaldırır. |
| [reset()](#reset--) | LayoutSlide üzerinde bir prototipi olan her şeklin konumunu, boyutunu ve biçimlendirmesini sıfırlar. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

Slaytın HeaderFooter yöneticisini döndürür. Salt-okunur [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Döndürür:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

Slaytın numarasını döndürür. [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) koleksiyonundaki slayt dizini her zaman SlideNumber - 1'e eşittir. Okunur/Yazılabilir int.

**Döndürür:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

Slaytın numarasını döndürür. [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) koleksiyonundaki slayt dizini her zaman SlideNumber - 1'e eşittir. Okunur/Yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Belirtilen slaytın slayt gösterimi sırasında gizli olup olmadığını belirler. Okunur/Yazılabilir boolean.

**Döndürür:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Belirtilen slaytın slayt gösterimi sırasında gizli olup olmadığını belirler. Okunur/Yazılabilir boolean.

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
| scaleX | float | Bu Küçük Resmi x ekseninde ölçeklemek için kullanılan değer. |
| scaleY | float | Bu Küçük Resmi y ekseninde ölçeklemek için kullanılan değer. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Görüntü nesnesi android.graphics.Bitmap

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Gerçek boyutun %20'si kadar bir Küçük Resim nesnesi döndürür.

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Görüntü nesnesi android.graphics.Bitmap

### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(Size imageSize)
```

Belirtilen boyutta bir görüntü nesnesi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Oluşturulacak görüntünün boyutu. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Bitmap nesnesi.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

Belirtilen parametrelerle bir Küçük Resim tiff bitmap nesnesi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff seçenekleri. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Görüntü nesnesi.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

Küçük Resim Bitmap nesnesi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Render seçenekleri. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Bitmap nesneleri.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Özel ölçekleme ile bir Küçük Resim Bitmap nesnesi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Render seçenekleri. |
| scaleX | float | Bu Küçük Resmi x ekseninde ölçeklemek için kullanılan değer. |
| scaleY | float | Bu Küçük Resmi y ekseninde ölçeklemek için kullanılan değer. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Bitmap nesneleri.

### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(IRenderingOptions options, Size imageSize)
```

Belirtilen boyutta bir Küçük Resim Bitmap nesnesi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Render seçenekleri. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Oluşturulacak görüntünün boyutu. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Bitmap nesneleri.

### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

Mevcut slayt için düzen slaytını döndürür veya ayarlar. Okunur/Yazılabilir [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

Mevcut slayt için düzen slaytını döndürür veya ayarlar. Okunur/Yazılabilir [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

Not slaytına erişim, ekleme ve kaldırma imkâni sağlar. Salt-okunur [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

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
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Bulunacak yorumların yazarı ya da tüm yorumları döndürmek için null. |

**Döndürür:**
com.aspose.slides.IComment[] - [IComment](../../com.aspose.slides/icomment) dizisi.

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

Sunumdan slaytı kaldırır.

### reset() {#reset--}
```
public abstract void reset()
```

LayoutSlide üzerinde bir prototipi olan her şeklin konumunu, boyutunu ve biçimlendirmesini sızerler.