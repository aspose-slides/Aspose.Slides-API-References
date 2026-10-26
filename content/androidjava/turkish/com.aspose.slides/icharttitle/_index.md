---
title: IChartTitle
second_title: Aspose.Slides for Android için Java API Referansı
description: Grafik başlığı özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/icharttitle/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

Grafik başlığı özelliklerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getOverlay()](#getOverlay--) | Diğer grafik öğelerinin başlığın üzerine gelmesine izin verilip verilmeyeceğini belirler. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Diğer grafik öğelerinin başlığın üzerine gelmesine izin verilip verilmeyeceğini belirler. |
| [getFormat()](#getFormat--) | Bir başlığın dolgu, çizgi ve efekt stillerini döndürür. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Diğer grafik öğelerinin başlığın üzerine gelmesine izin verilip verilmeyeceğini belirler. Okuma/yazma boolean.

**Döndürür:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Diğer grafik öğelerinin başlığın üzerine gelmesine izin verilip verilmeyeceğini belirler. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Bir başlığın dolgu, çizgi ve efekt stillerini döndürür. Salt-okunur [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)