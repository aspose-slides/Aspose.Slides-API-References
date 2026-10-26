---
title: XpsOptions
second_title: Aspose.Slides for Java API Referansı
description: Sunumun XPS biçiminde nasıl kaydedileceğini kontrol eden seçenekler sağlar.
type: docs
url: /tr/com.aspose.slides/xpsoptions/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

Bir sunumun XPS biçiminde nasıl kaydedileceğini kontrol eden seçenekler sağlar.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // Bir sunum dosyasını temsil eden Presentation nesnesi oluşturur
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // Sunumu XPS belgesine kaydeder
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // Bir sunum dosyasını temsil eden Presentation nesnesi oluşturur
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // TiffOptions sınıfını oluşturur
>      XpsOptions options = new XpsOptions();
>      // MetaDosyaları PNG olarak kaydeder
>      options.setSaveMetafilesAsPng(true);
>      // Sunumu XPS belgesine kaydeder
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | Varsayılan yapıcı. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Sunumda kullanılan tüm metadosyaları PNG görüntülerine dönüştürmek için doğru. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Sunumda kullanılan tüm metadosyaları PNG görüntülerine dönüştürmek için doğru. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Her slaytın etrafına siyah çerçeve çizmek için doğru. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Her slaytın etrafına siyah çerçeve çizmek için doğru. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```


Varsayılan yapıcı.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan değeri false.

**Döndürür:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan değeri false.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```


Sunumda kullanılan tüm metadosyaları PNG görüntülerine dönüştürmek için doğru. Okunur/yazılabilir boolean.

--------------------

Varsayılan **true**.

**Döndürür:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```


Sunumda kullanılan tüm metadosyaları PNG görüntülerine dönüştürmek için doğru. Okunur/yazılabilir boolean.

--------------------

Varsayılan **true**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```


Her slaytın etrafına siyah çerçeve çizmek için doğru. Okunur/yazılabilir boolean.

--------------------

Varsayılan **false**.

**Döndürür:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```


Her slaytın etrafına siyah çerçeve çizmek için doğru. Okunur/yazılabilir boolean.

--------------------

Varsayılan **false**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |