---
title: IChartTitle
second_title: Aspose.Slides for Java API Referansı
description: Grafik başlığı özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/icharttitle/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

Bir grafik başlığı özelliklerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getOverlay()](#getOverlay--) | Diğer grafik öğelerinin başlıkla çakışmasına izin verilip verilmeyeceğini belirler. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Diğer grafik öğelerinin başlıkla çakışmasına izin verilip verilmeyeceğini belirler. |
| [getFormat()](#getFormat--) | Bir başlığın doldurma, çizgi ve efekt stillerini döndürür. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Diğer grafik öğelerinin başlıkla çakışmasına izin verilip verilmeyeceğini belirler. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Diğer grafik öğelerinin başlıkla çakışmasına izin verilip verilmeyeceğini belirler. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Bir başlığın doldurma, çizgi ve efekt stillerini döndürür. Salt okunur [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)