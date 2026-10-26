---
title: SVGOptions
second_title: Aspose.Slides for Android via Java API Referansı
description: SVG seçeneklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/svgoptions/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

Bir SVG seçeneğini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | SVGOptions sınıfının yeni bir örneğini başlatır. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | SVGOptions sınıfının yeni bir örneğini, bağlantı yerleştirme denetleyicisi nesnesini belirterek başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekleri sağlar. |
| [getUseFrameSize()](#getUseFrameSize--) | Metin çerçevesinin bir renderleme alanına dahil edilip edilmeyeceğini belirler. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Metin çerçevesinin bir renderleme alanına dahil edilip edilmeyeceğini belirler. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Renderleme sırasında şeklin belirtilen döndürmesinin uygulanıp uygulanmayacağını belirler. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Renderleme sırasında şeklin belirtilen döndürmesinin uygulanıp uygulanmayacağını belirler. |
| [getVectorizeText()](#getVectorizeText--) | Slayttaki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Slayttaki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Metafile rasterleştirme için alt çözünürlük sınırını alır veya ayarlar. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Metafile rasterleştirme için alt çözünürlük sınırını alır veya ayarlar. |
| [getDisable3DText()](#getDisable3DText--) | SVG'de 3B metnin devre dışı bırakılıp bırakılmadığını belirler. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | SVG'de 3B metnin devre dışı bırakılıp bırakılmadığını belirler. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | FromCornerX ve FromCenter gradyanlarının bölünmesini devre dışı bırakır. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | FromCornerX ve FromCenter gradyanlarının bölünmesini devre dışı bırakır. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1, işaretçiler için iç kenar boşlukları tanımlama yeteneğine sahip değildir. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1, işaretçiler için iç kenar boşlukları tanımlama yeteneğine sahip değildir. |
| [getDefault()](#getDefault--) | Varsayılan ayarları döndürür. |
| [getSimple()](#getSimple--) | En basit ve en küçük SVG dosyası oluşturulması için ayarları döndürür. |
| [getWYSIWYG()](#getWYSIWYG--) | En doğru SVG dosyası oluşturulması için ayarları döndürür. |
| [getJpegQuality()](#getJpegQuality--) | JPEG kodlama kalitesini belirler. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | JPEG kodlama kalitesini belirler. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Kullanıcının şekil dönüşümünü kontrol etmesini sağlayan bir geri çağırma arayüzünü alır ve ayarlar. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Kullanıcının şekil dönüşümünü kontrol etmesini sağlayan bir geri çağırma arayüzünü alır ve ayarlar. |
| [getPicturesCompression()](#getPicturesCompression--) | Resim sıkıştırma seviyesini temsil eder |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Resim sıkıştırma seviyesini temsil eder |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Kırpılmış parçaların belgenin bir parçası olarak kalıp kalmayacağını belirten bir boolean bayrağı. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Kırpılmış parçaların belgenin bir parçası olarak kalıp kalmayacağını belirten bir boolean bayrağı. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Harici yüklenen yazı tiplerinin nasıl işleneceğini belirler. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Harici yüklenen yazı tiplerinin nasıl işleneceğini belirler. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Metnin ligatürler kullanılmadan işlenip işlenmediğini gösteren değeri alır veya ayarlar. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Metnin ligatürler kullanılmadan işlenip işlenmediğini gösteren değeri alır veya ayarlar. |
### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```


SVGOptions sınıfının yeni bir örneğini başlatır.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```


SVGOptions sınıfının yeni bir örneğini, bağlantı yerleştirme denetleyicisi nesnesini belirterek başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Bağlantı yerleştirme denetleyicisi referansı. |

--------------------

Bağlantı yerleştirme denetleyicisi, kaynakların (örneğin resimler) yerleştirilip yerleştirilmeyeceği veya dış kaynak olarak referans verilip verilmeyeceği kararlarını veren bir temsilci nesnedir. |

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


Metin çerçevesinin bir renderleme alanına dahil edilip edilmeyeceğini belirler. Okunur/Yazılabilir boolean. Öntanımlı değer false'tur.

**Döndürür:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```


Metin çerçevesinin bir renderleme alanına dahil edilip edilmeyeceğini belirler. Okunur/Yazılabilir boolean. Öntanımlı değer false'tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```


Renderleme sırasında şeklin belirtilen döndürmesinin uygulanıp uygulanmayacağını belirler. Okunur/Yazılabilir boolean. Öntanımlı değer true'dir.

**Döndürür:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```


Renderleme sırasında şeklin belirtilen döndürmesinin uygulanıp uygulanmayacağını belirler. Okunur/Yazılabilir boolean. Öntanımlı değer true'dir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```


Slayttaki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler. Okunur/Yazılabilir boolean.

**Döndürür:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```


Slayttaki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler. Okunur/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```


Metafile rasterleştirme için alt çözünürlük sınırını alır veya ayarlar. Okunur/Yazılabilir int.

**Döndürür:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```


Metafile rasterleştirme için alt çözünürlük sınırını alır veya ayarlar. Okunur/Yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```


SVG'de 3B metnin devre dışı bırakılıp bırakılmadığını belirler. Okunur/Yazılabilir boolean.

**Döndürür:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```


SVG'de 3B metnin devre dışı bırakılıp bırakılmadığını belirler. Okunur/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```


FromCornerX ve FromCenter gradyanlarının bölünmesini devre dışı bırakır. Okunur/Yazılabilir boolean.

**Döndürür:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```


FromCornerX ve FromCenter gradyanlarının bölünmesini devre dışı bırakır. Okunur/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```


SVG 1.1, işaretçiler için iç kenar boşlukları tanımlama yeteneğine sahip değildir. Aspose.Slides SVG yazma motoru bu sorunu çözmek için satırın ok ucunu kırpar, böylece satır işaretçilerle örtüşmez. Bu seçenek bu davranışı kapatır. Okunur/Yazılabilir boolean.

**Döndürür:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```


SVG 1.1, işaretçiler için iç kenar boşlukları tanımlama yeteneğine sahip değildir. Aspose.Slides SVG yazma motoru bu sorunu çözmek için satırın ok ucunu kırpar, böylece satır işaretçilerle örtüşmez. Bu seçenek bu davranışı kapatır. Okunur/Yazılabilir boolean.

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


En basit ve en küçük SVG dosyası oluşturulması için ayarları döndürür. Salt-okunur [SVGOptions](../../com.aspose.slides/svgoptions).

**Döndürür:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```


En doğru SVG dosyası oluşturulması için ayarları döndürür. Salt-okunur [SVGOptions](../../com.aspose.slides/svgoptions).

**Döndürür:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```


JPEG kodlama kalitesini belirler. Okunur/Yazılabilir int.

**Döndürür:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```


JPEG kodlama kalitesini belirler. Okunur/Yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```


Kullanıcının şekil dönüşümünü kontrol etmesini sağlayan bir geri çağırma arayüzünü alır ve ayarlar. Okunur/Yazılabilir [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Döndürür:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```


Kullanıcının şekil dönüşümünü kontrol etmesini sağlayan bir geri çağırma arayüzünü alır ve ayarlar. Okunur/Yazılabilir [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

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


Kırpılmış parçaların belgenin bir parçası olarak kalıp kalmayacağını belirten bir boolean bayrağı. Değer true ise kırpılmış parçalar kaldırılır, false ise belge içinde serileştirilir (bu daha büyük bir dosyaya yol açabilir)

**Döndürür:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```


Kırpılmış parçaların belgenin bir parçası olarak kalıp kalmayacağını belirten bir boolean bayrağı. Değer true ise kırpılmış parçalar kaldırılır, false ise belge içinde serileştirilir (bu daha büyük bir dosyaya yol açabilir)

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```


Harici yüklenen yazı tiplerinin nasıl işleneceğini belirler. Okunur/Yazılabilir [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Döndürür:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```


Harici yüklenen yazı tiplerinin nasıl işleneceğini belirler. Okunur/Yazılabilir [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```


Metnin ligatürler kullanılmadan işlenip işlenmediğini gösteren değeri alır veya ayarlar. Değer true ise ligatürler devre dışı bırakılır. Varsayılan olarak bu özellik false olarak ayarlanmıştır.

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


Metnin ligatürler kullanılmadan işlenip işlenmediğini gösteren değeri alır veya ayarlar. Değer true ise ligatürler devre dışı bırakılır. Varsayılan olarak bu özellik false olarak ayarlanmıştır.

--------------------

> ```
public final void setDisableFontLigatures(boolean value)
```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |