---
title: IXpsOptions
second_title: Aspose.Slides for Java API Referansı
description: Bir sunumun XPS formatında nasıl kaydedileceğini kontrol eden seçenekler sağlar.
type: docs
url: /tr/com.aspose.slides/ixpsoptions/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

Sunumun XPS biçiminde kaydedilmesini kontrol eden seçenekler sağlar.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True bir sunumda kullanılan tüm metafileları PNG görüntülerine dönüştürmek için. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True bir sunumda kullanılan tüm metafileları PNG görüntülerine dönüştürmek için. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True her slaytın etrafına siyah çerçeve çizmek için. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True her slaytın etrafına siyah çerçeve çizmek için. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True bir sunumda kullanılan tüm metafileları PNG görüntülerine dönüştürmek için. Okuma/yazma boolean.

--------------------

Varsayılan **true**.

**Dönen Değer:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True bir sunumda kullanılan tüm metafileları PNG görüntülerine dönüştürmek için. Okuma/yazma boolean.

--------------------

Varsayılan **true**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True her slaytın etrafına siyah çerçeve çizmek için. Okuma/yazma boolean.

--------------------

Varsayılan **false**.

**Dönen Değer:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True her slaytın etrafına siyah çerçeve çizmek için. Okuma/yazma boolean.

--------------------

Varsayılan **false**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan **false**.

**Dönen Değer:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan **false**.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |