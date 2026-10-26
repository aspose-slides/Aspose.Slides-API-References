---
title: IXpsOptions
second_title: Aspose.Slides for Android için Java API Referansı
description: Bir sunumun XPS formatında nasıl kaydedileceğini kontrol eden seçenekler sağlar.
type: docs
url: /tr/com.aspose.slides/ixpsoptions/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

Bir sunumun XPS formatında nasıl kaydedileceğini kontrol eden seçenekleri sağlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Doğru, sunumda kullanılan tüm metafile'ları PNG görüntülerine dönüştürmek için. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Doğru, sunumda kullanılan tüm metafile'ları PNG görüntülerine dönüştürmek için. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Doğru, her slaytın etrafına siyah bir çerçeve çizmek için. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Doğru, her slaytın etrafına siyah bir çerçeve çizmek için. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

Doğru, sunumda kullanılan tüm metafile'ları PNG görüntülerine dönüştürmek için. Okunabilir/Yazılabilir boolean.

--------------------

Varsayılan **true**.

**Döndürür:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

Doğru, sunumda kullanılan tüm metafile'ları PNG görüntülerine dönüştürmek için. Okunabilir/Yazılabilir boolean.

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

Doğru, her slaytın etrafına siyah bir çerçeve çizmek için. Okunabilir/Yazılabilir boolean.

--------------------

Varsayılan **false**.

**Döndürür:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

Doğru, her slaytın etrafına siyah bir çerçeve çizmek için. Okunabilir/Yazılabilir boolean.

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

**Döndürür:**
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