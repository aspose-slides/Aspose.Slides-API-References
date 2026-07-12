---
title: ISVGOptions
second_title: Aspose.Slides for Android Java API Referansı
description: SVG seçeneklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/isvgoptions/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

SVG seçeneklerini temsil eder.

## Yöntemler

| Method | Description |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | Bir slayttaki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Bir slayttaki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Metafile rasterleştirme için alt çözünürlük sınırını döndürür veya ayarlar. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Metafile rasterleştirme için alt çözünürlük sınırını döndürür veya ayarlar. |
| [getDisable3DText()](#getDisable3DText--) | SVG içinde 3D metnin devre dışı bırakılıp bırakılmadığını belirler. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | SVG içinde 3D metnin devre dışı bırakılıp bırakılmadığını belirler. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | FromCornerX ve FromCenter gradyanlarının bölünmesini devre dışı bırakır. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | FromCornerX ve FromCenter gradyanlarının bölünmesini devre dışı bırakır. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1, işaretçiler için iç boşluk tanımlama yeteneğine sahip değildir. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1, işaretçiler için iç boşluk tanımlama yeteneğine sahip değildir. |
| [getJpegQuality()](#getJpegQuality--) | JPEG kodlama kalitesini belirler. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | JPEG kodlama kalitesini belirler. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Kullanıcının şekil dönüştürmesini kontrol etmesine izin veren bir geriçağırım arayüzünü döndürür ve ayarlar. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Kullanıcının şekil dönüştürmesini kontrol etmesine izin veren bir geriçağırım arayüzünü döndürür ve ayarlar. |
| [getPicturesCompression()](#getPicturesCompression--) | Resim sıkıştırma seviyesini temsil eder Okunur/yazılır \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Resim sıkıştırma seviyesini temsil eder Okunur/yazılır \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Kırpılmış parçaların belgenin bir parçası olarak kalıp kalmadığını gösteren bir boolean işareti. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Kırpılmış parçaların belgenin bir parçası olarak kalıp kalmadığını gösteren bir boolean işareti. |
| [getUseFrameSize()](#getUseFrameSize--) | Metin çerçevesinin renderleme alanına dahil edilip edilmeyeceğini belirler. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Metin çerçevesinin renderleme alanına dahil edilip edilmeyeceğini belirler. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Renderleme sırasında şeklin belirtilen döndürülmesinin uygulanıp uygulanmayacağını belirler. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Renderleme sırasında şeklin belirtilen döndürülmesinin uygulanıp uygulanmayacağını belirler. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Harici yüklenen yazı tiplerinin nasıl işleneceğini belirler. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Harici yüklenen yazı tiplerinin nasıl işleneceğini belirler. |
| [getInkOptions()](#getInkOptions--) | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Metnin ligatür kullanmadan renderlenip renderlenmediğini gösteren bir değeri alır veya ayarlar. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Metnin ligatür kullanmadan renderlenip renderlenmediğini gösteren bir değeri alır veya ayarlar. |

### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

Bir slayttaki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler. Okunur/yazılır boolean.

**Döndürür:**
boolean

### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

Bir slayttaki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

Metafile rasterleştirme için alt çözünürlük sınırını döndürür veya ayarlar. Okunur/yazılır int.

**Döndürür:**
int

### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

Metafile rasterleştirme için alt çözünürlük sınırını döndürür veya ayarlar. Okunur/yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

SVG içinde 3D metnin devre dışı bırakılıp bırakılmadığını belirler. Okunur/yazılır boolean.

**Döndürür:**
boolean

### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

SVG içinde 3D metnin devre dışı bırakılıp bırakılmadığını belirler. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

FromCornerX ve FromCenter gradyanlarının bölünmesini devre dışı bırakır. Okunur/yazılır boolean.

**Döndürür:**
boolean

### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

FromCornerX ve FromCenter gradyanlarının bölünmesini devre dışı bırakır. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1, işaretçiler için iç boşluk tanımlama yeteneğine sahip değildir. Aspose.Slides SVG yazma motoru bu sorun için bir çözüm sunar: oklu çizginin ucunu kırpar, böylece çizgi işaretçilerin üzerine binmez. Bu seçenek bu davranışı kapatır. Okunur/yazılır boolean.

**Döndürür:**
boolean

### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1, işaretçiler için iç boşluk tanımlama yeteneğine sahip değildir. Aspose.Slides SVG yazma motoru bu sorun için bir çözüm sunar: oklu çizginin ucunu kırpar, böylece çizgi işaretçilerin üzerine binmez. Bu seçenek bu davranışı kapatır. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

JPEG kodlama kalitesini belirler. Okunur/yazılır int.

**Döndürür:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

JPEG kodlama kalitesini belirler. Okunur/yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

Kullanıcının şekil dönüştürmesini kontrol etmesine izin veren bir geriçağırım arayüzünü döndürür ve ayarlar. Okunur/yazılır [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Döndürür:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)

### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

Kullanıcının şekil dönüştürmesini kontrol etmesine izin veren bir geriçağırım arayüzünü döndürür ve ayarlar. Okunur/yazılır [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Resim sıkıştırma seviyesini temsil eder Okunur/yazılır \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Döndürür:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Resim sıkıştırma seviyesini temsil eder Okunur/yazılır \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Kırpılmış parçaların belgenin bir parçası olarak kalıp kalmadığını gösteren bir boolean işareti. true ise kırpılmış parçalar kaldırılacak, false ise belge içinde serileştirilecektir (bu daha büyük bir dosyaya yol açabilir). Okunur/yazılır boolean.

**Döndürür:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Kırpılmış parçaların belgenin bir parçası olarak kalıp kalmadığını gösteren bir boolean işareti. true ise kırpılmış parçalar kaldırılacak, false ise belge içinde serileştirilecektir (bu daha büyük bir dosyaya yol açabilir). Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

Metin çerçevesinin renderleme alanına dahil edilip edilmeyeceğini belirler. Okunur/yazılır boolean. Varsayılan değer false'tur.

**Döndürür:**
boolean

### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

Metin çerçevesinin renderleme alanına dahil edilip edilmeyeceğini belirler. Okunur/yazılır boolean. Varsayılan değer false'tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

Renderleme sırasında şeklin belirtilen döndürülmesinin uygulanıp uygulanmayacağını belirler. Okunur/yazılır boolean. Varsayılan değer true'tur.

**Döndürür:**
boolean

### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

Renderleme sırasında şeklin belirtilen döndürülmesinin uygulanıp uygulanmayacağını belirler. Okunur/yazılır boolean. Varsayılan değer true'tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

Harici yüklenen yazı tiplerinin nasıl işleneceğini belirler. Okunur/yazılır [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Döndürür:**
int

### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

Harici yüklenen yazı tiplerinin nasıl işleneceğini belirler. Okunur/yazılır [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. Sadece okunur [IInkOptions](../../com.aspose.slides/iinkoptions)

**Döndürür:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Metnin ligatür kullanmadan renderlenip renderlenmediğini gösteren bir değeri alır veya ayarlar. true olarak ayarlandığında, ligatürler render edilen çıktıda devre dışı bırakılır. Varsayılan olarak bu özellik false olarak ayarlanmıştır.

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
public abstract void setDisableFontLigatures(boolean value)
```

Metnin ligatür kullanmadan renderlenip renderlenmediğini gösteren bir değeri alır veya ayarlar. true olarak ayarlandığında, ligatürler render edilen çıktıda devre dışı bırakılır. Varsayılan olarak bu özellik false olarak ayarlanmıştır.

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