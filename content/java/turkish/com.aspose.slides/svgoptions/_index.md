---
title: SVGOptions
second_title: Aspose.Slides for Java API Referansı
description: SVG seçeneklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/svgoptions/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

SVG seçeneklerini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | SVGOptions sınıfının yeni bir örneğini başlatır. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Bağlantı gömme denetleyici nesnesini belirterek SVGOptions sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar. |
| [getUseFrameSize()](#getUseFrameSize--) | Metin çerçevesinin bir render alanına dahil edilip edilmeyeceğini belirler. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Metin çerçevesinin bir render alanına dahil edilip edilmeyeceğini belirler. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Render sırasında şeklin belirtilen dönüşünün uygulanıp uygulanmayacağını belirler. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Render sırasında şeklin belirtilen dönüşünün uygulanıp uygulanmayacağını belirler. |
| [getVectorizeText()](#getVectorizeText--) | Slayttaki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Slayttaki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Metafile rasterleştirmesi için alt çözünürlük sınırını alır veya ayarlar. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Metafile rasterleştirmesi için alt çözünürlük sınırını alır veya ayarlar. |
| [getDisable3DText()](#getDisable3DText--) | SVG'de 3D metnin devre dışı bırakılıp bırakılmadığını belirler. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | SVG'de 3D metnin devre dışı bırakılıp bırakılmadığını belirler. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | FromCornerX ve FromCenter gradyanlarının bölünmesini devre dışı bırakır. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | FromCornerX ve FromCenter gradyanlarının bölünmesini devre dışı bırakır. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 işaretçiler için iç kenar tanımlama yeteneğine sahip değildir. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 işaretçiler için iç kenar tanımlama yeteneğine sahip değildir. |
| [getDefault()](#getDefault--) | Varsayılan ayarları döndürür. |
| [getSimple()](#getSimple--) | En basit ve en küçük SVG dosyası oluşturma ayarlarını döndürür. |
| [getWYSIWYG()](#getWYSIWYG--) | En doğru SVG dosyası oluşturma ayarlarını döndürür. |
| [getJpegQuality()](#getJpegQuality--) | JPEG kodlama kalitesini belirler. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | JPEG kodlama kalitesini belirler. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Kullanıcının şekil dönüşümünü kontrol etmesini sağlayan bir geri çağırma arayüzünü alır ve ayarlar. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Kullanıcının şekil dönüşümünü kontrol etmesini sağlayan bir geri çağırma arayüzünü alır ve ayarlar. |
| [getPicturesCompression()](#getPicturesCompression--) | Resim sıkıştırma seviyesini temsil eder |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Resim sıkıştırma seviyesini temsil eder |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Kesilen bölümlerin belgenin bir parçası olarak kalıp kalmayacağını belirten bir boolean işareti. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Kesilen bölümlerin belgenin bir parçası olarak kalıp kalmayacağını belirten bir boolean işareti. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Harici yüklenen yazı tiplerinin işlenme şeklini belirler. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Harici yüklenen yazı tiplerinin işlenme şeklini belirler. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Metnin ligaturler kullanılmadan render edilip edilmediğini gösteren bir değeri alır veya ayarlar. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Metnin ligaturler kullanılmadan render edilip edilmediğini gösteren bir değeri alır veya ayarlar. |
### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```


SVGOptions sınıfının yeni bir örneğini başlatır.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```


Bağlantı gömme denetleyici nesnesini belirterek SVGOptions sınıfının yeni bir örneğini başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Bağlantı gömme denetleyici referansı.

--------------------

Bağlantı gömme denetleyicisi, kaynakların (görseller gibi) gömülmesi mi yoksa harici kaynak olarak referans gösterilmesi mi gerektiğine karar veren bir temsilci nesnedir. |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar. Salt-okunur [IInkOptions](../../com.aspose.slides/iinkoptions)

**Döndürür:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```


Metin çerçevesinin bir render alanına dahil edilip edilmeyeceğini belirler. Okunur/yazılabilir boolean. Varsayılan değer false.

**Döndürür:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```


Metin çerçevesinin bir render alanına dahil edilip edilmeyeceğini belirler. Okunur/yazılabilir boolean. Varsayılan değer false.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```


Render sırasında şeklin belirtilen dönüşünün uygulanıp uygulanmayacağını belirler. Okunur/yazılabilir boolean. Varsayılan değer true.

**Döndürür:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```


Render sırasında şeklin belirtilen dönüşünün uygulanıp uygulanmayacağını belirler. Okunur/yazılabilir boolean. Varsayılan değer true.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```


Slayttaki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```


Slayttaki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```


Metafile rasterleştirmesi için alt çözünürlük sınırını alır veya ayarlar. Okunur/yazılabilir int.

**Döndürür:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```


Metafile rasterleştirmesi için alt çözünürlük sınırını alır veya ayarlar. Okunur/yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```


SVG'de 3D metnin devre dışı bırakılıp bırakılmadığını belirler. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```


SVG'de 3D metnin devre dışı bırakılıp bırakılmadığını belirler. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```


FromCornerX ve FromCenter gradyanlarının bölünmesini devre dışı bırakır. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```


FromCornerX ve FromCenter gradyanlarının bölünmesini devre dışı bırakır. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```


SVG 1.1 işaretçiler için iç kenar tanımlama yeteneğine sahip değildir. Aspose.Slides SVG yazma motoru bu sorunu çözmek için çizgi uçlarını okla kırpar, böylece çizgi işaretçileriyle çakışmaz. Bu seçenek bu davranışı kapatır. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```


SVG 1.1 işaretçiler için iç kenar tanımlama yeteneğine sahip değildir. Aspose.Slides SVG yazma motoru bu sorunu çözmek için çizgi uçlarını okla kırpar, böylece çizgi işaretçileriyle çakışmaz. Bu seçenek bu davranışı kapatır. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```


Varsayılan ayarları döndürür. Salt-okunur [SVGOptions](../../com.aspose.slides/svgoptions).

**Döndürür:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```


En basit ve en küçük SVG dosyası oluşturma ayarlarını döndürür. Salt-okunur [SVGOptions](../../com.aspose.slides/svgoptions).

**Döndürür:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```


En doğru SVG dosyası oluşturma ayarlarını döndürür. Salt-okunur [SVGOptions](../../com.aspose.slides/svgoptions).

**Döndürür:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```


JPEG kodlama kalitesini belirler. Okunur/yazılabilir int.

**Döndürür:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```


JPEG kodlama kalitesini belirler. Okunur/yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```


Kullanıcının şekil dönüşümünü kontrol etmesini sağlayan bir geri çağırma arayüzünü alır ve ayarlar. Okunur/yazılabilir [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Döndürür:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```


Kullanıcının şekil dönüşümünü kontrol etmesini sağlayan bir geri çağırma arayüzünü alır ve ayarlar. Okunur/yazılabilir [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```


Resim sıkıştırma seviyesini temsil eder

**Döndürür:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```


Resim sıkıştırma seviyesini temsil eder

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```


Kesilen bölümlerin belgenin bir parçası olarak kalıp kalmayacağını belirten bir boolean işareti. true ise kesilen bölümler kaldırılır, false ise belge içinde serileştirilir (bu dosyanın daha büyük olmasına yol açabilir)

**Döndürür:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```


Kesilen bölümlerin belgenin bir parçası olarak kalıp kalmayacağını belirten bir boolean işareti. true ise kesilen bölümler kaldırılır, false ise belge içinde serileştirilir (bu dosyanın daha büyük olmasına yol açabilir)

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```


Harici yüklenen yazı tiplerinin işlenme şeklini belirler. Okunur/yazılabilir [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Döndürür:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```


Harici yüklenen yazı tiplerinin işlenme şeklini belirler. Okunur/yazılabilir [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```


Metnin ligaturler kullanılmadan render edilip edilmediğini gösteren bir değeri alır veya ayarlar. true olduğunda ligaturler render çıktısında devre dışı bırakılır. Varsayılan olarak bu özellik false'tir.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```


Metnin ligaturler kullanılmadan render edilip edilmediğini gösteren bir değeri alır veya ayarlar. true olduğunda ligaturler render çıktısında devre dışı bırakılır. Varsayılan olarak bu özellik false'tir.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |