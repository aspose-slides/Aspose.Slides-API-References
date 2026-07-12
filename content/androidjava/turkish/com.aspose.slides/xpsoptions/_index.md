---
title: XpsOptions
second_title: Aspose.Slides for Android Java API Referansı
description: Bir sunumun XPS formatında nasıl kaydedileceğini kontrol eden seçenekleri sağlar.
type: docs
url: /tr/com.aspose.slides/xpsoptions/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

Sunumun XPS formatında nasıl kaydedileceğini kontrol eden seçenekleri sağlar.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // Bir sunum dosyasını temsil eden Presentation nesnesi oluşturur
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // Sunumu XPS belgesine kaydediyor
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
>      // MetaFiles'i PNG olarak kaydeder
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
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Sunumda kullanılan tüm metafilleri PNG görsellerine dönüştürmek için **true**. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Sunumda kullanılan tüm metafilleri PNG görsellerine dönüştürmek için **true**. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Her slaytın etrafına siyah çerçeve çizmek için **true**. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Her slaytın etrafına siyah çerçeve çizmek için **true**. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

Varsayılan yapıcı.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan **false**.

**Döndürür:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan **false**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

Sunumda kullanılan tüm metafilleri PNG görsellerine dönüştürmek için **true**. Okunur/Yazılabilir boolean.

--------------------

Varsayılan **true**.

**Döndürür:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

Sunumda kullanılan tüm metafilleri PNG görsellerine dönüştürmek için **true**. Okunur/Yazılabilir boolean.

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

Her slaytın etrafına siyah çerçeve çizmek için **true**. Okunur/Yazılabilir boolean.

--------------------

Varsayılan **false**.

**Döndürür:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

Her slaytın etrafına siyah çerçeve çizmek için **true**. Okunur/Yazılabilir boolean.

--------------------

Varsayılan **false**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |