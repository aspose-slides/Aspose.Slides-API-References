---
title: ISVGOptions
second_title: Aspose.Slides for Java API Referansı
description: Bir SVG seçeneğini temsil eder.
type: docs
url: /tr/com.aspose.slides/isvgoptions/
---
**All Implemented Interfaces:**
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
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Metafile rasterleştirme için alt çözünürlük limitini alır veya ayarlar. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Metafile rasterleştirme için alt çözünürlük limitini alır veya ayarlar. |
| [getDisable3DText()](#getDisable3DText--) | SVG'de 3D metnin devre dışı bırakılıp bırakılmayacağını belirler. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | SVG'de 3D metnin devre dışı bırakılıp bırakılmayacağını belirler. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | FromCornerX ve FromCenter geçişlerinin bölünmesini devre dışı bırakır. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | FromCornerX ve FromCenter geçişlerinin bölünmesini devre dışı bırakır. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 işaretçiler için iç boşluk tanımlama yeteneğine sahip değildir. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 işaretçiler için iç boşluk tanımlama yeteneğine sahip değildir. |
| [getJpegQuality()](#getJpegQuality--) | JPEG kodlama kalitesini belirler. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | JPEG kodlama kalitesini belirler. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Kullanıcının şekil dönüşümünü kontrol etmesine izin veren bir geri çağırma arayüzünü alır ve ayarlar. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Kullanıcının şekil dönüşümünü kontrol etmesine izin veren bir geri çağırma arayüzünü alır ve ayarlar. |
| [getPicturesCompression()](#getPicturesCompression--) | Resim sıkıştırma seviyesini temsil eder Okuma/Yazma \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Resim sıkıştırma seviyesini temsil eder Okuma/Yazma \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Kırpılmış bölümlerin belgenin bir parçası olarak kalıp kalmayacağını gösteren bir Boolean bayrağı. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Kırpılmış bölümlerin belgenin bir parçası olarak kalıp kalmayacağını gösteren bir Boolean bayrağı. |
| [getUseFrameSize()](#getUseFrameSize--) | Metin çerçevesinin bir renderleme alanına dahil edilip edilmemeyeceğini belirler. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Metin çerçevesinin bir renderleme alanına dahil edilip edilmemeyeceğini belirler. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Renderleme sırasında şeklin belirtilen dönüşünün uygulanıp uygulanmayacağını belirler. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Renderleme sırasında şeklin belirtilen dönüşünün uygulanıp uygulanmayacağını belirler. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Dışarıdan yüklenen yazı tiplerinin nasıl işleneceğini belirler. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Dışarıdan yüklenen yazı tiplerinin nasıl işleneceğini belirler. |
| [getInkOptions()](#getInkOptions--) | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Metnin ligatürler kullanılmadan renderlenip renderlenmeyeceğini belirten bir değeri alır veya ayarlar. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Metnin ligatürler kullanılmadan renderlenip renderlenmeyeceğini belirten bir değeri alır veya ayarlar. |
### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

Bir slayttaki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler. Okuma/Yazma boolean.

**Döndürür:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

Bir slayttaki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

Metafile rasterleştirme için alt çözünürlük limitini alır veya ayarlar. Okuma/Yazma int.

**Döndürür:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

Metafile rasterleştirme için alt çözünürlük limitini alır veya ayarlar. Okuma/Yazma int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

SVG'de 3D metnin devre dışı bırakılıp bırakılmayacağını belirler. Okuma/Yazma boolean.

**Döndürür:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

SVG'de 3D metnin devre dışı bırakılıp bırakılmayacağını belirler. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

FromCornerX ve FromCenter geçişlerinin bölünmesini devre dışı bırakır. Okuma/Yazma boolean.

**Döndürür:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

FromCornerX ve FromCenter geçişlerinin bölünmesini devre dışı bırakır. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 işaretçiler için iç boşluk tanımlama yeteneğine sahip değildir. Aspose.Slides SVG yazma motoru bu sorunu çözmek için satırın ok ucunu kırpar, böylece satır işaretçileri çakışmaz. Bu seçenek bu davranışı kapatır. Okuma/Yazma boolean.

**Döndürür:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 işaretçiler için iç boşluk tanımlama yeteneğine sahip değildir. Aspose.Slides SVG yazma motoru bu sorunu çözmek için satırın ok ucunu kırpar, böylece satır işaretçileri çakışmaz. Bu seçenek bu davranışı kapatır. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

JPEG kodlama kalitesini belirler. Okuma/Yazma int.

**Döndürür:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

JPEG kodlama kalitesini belirler. Okuma/Yazma int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

Kullanıcının şekil dönüşümünü kontrol etmesine izin veren bir geri çağırma arayüzünü alır ve ayarlar. Okuma/Yazma [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Döndürür:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

Kullanıcının şekil dönüşümünü kontrol etmesine izin veren bir geri çağırma arayüzünü alır ve ayarlar. Okuma/Yazma [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |
### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Resim sıkıştırma seviyesini temsil eder Okuma/Yazma \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Döndürür:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Resim sıkıştırma seviyesini temsil eder Okuma/Yazma \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Kırpılmış bölümlerin belgenin bir parçası olarak kalıp kalmayacağını gösteren bir Boolean bayrağı. True ise kırpılmış bölümler kaldırılır, false ise belgede serileştirilir (bu dosya boyutunu artırabilir). Okuma/Yazma boolean.

**Döndürür:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Kırpılmış bölümlerin belgenin bir parçası olarak kalıp kalmayacağını gösteren bir Boolean bayrağı. True ise kırpılmış bölümler kaldırılır, false ise belgede serileştirilir (bu dosya boyutunu artırabilir). Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

Metin çerçevesinin bir renderleme alanına dahil edilip edilmemeyeceğini belirler. Okuma/Yazma  boolean . Varsayılan değer false'tur.

**Döndürür:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

Metin çerçevesinin bir renderleme alanına dahil edilip edilmemeyeceğini belirler. Okuma/Yazma  boolean . Varsayılan değer false'tur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

Renderleme sırasında şeklin belirtilen dönüşünün uygulanıp uygulanmayacağını belirler. Okuma/Yazma  boolean . Varsayılan değer true'dir.

**Döndürür:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

Renderleme sırasında şeklin belirtilen dönüşünün uygulanıp uygulanmayacağını belirler. Okuma/Yazma  boolean . Varsayılan değer true'dir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

Dışarıdan yüklenen yazı tiplerinin nasıl işleneceğini belirler. Okuma/Yazma [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Döndürür:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

Dışarıdan yüklenen yazı tiplerinin nasıl işleneceğini belirler. Okuma/Yazma [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. Sadece-okunur [IInkOptions](../../com.aspose.slides/iinkoptions)

**Döndürür:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Metnin ligatürler kullanılmadan renderlenip renderlenmeyeceğini belirten bir değeri alır veya ayarlar. True olduğunda ligatürler render çıktısında devre dışı bırakılır. Varsayılan olarak bu özellik false'tir.

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

Metnin ligatürler kullanılmadan renderlenip renderlenmeyeceğini belirten bir değeri alır veya ayarlar. True olduğunda ligatürler render çıktısında devre dışı bırakılır. Varsayılan olarak bu özellik false'tir.

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