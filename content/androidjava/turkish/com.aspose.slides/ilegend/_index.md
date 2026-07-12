---
title: ILegend
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Grafik lejand özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/ilegend/
---
**Tüm Gerçekleştirilmiş Arayüzler:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

Grafiğin lejand özelliklerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getOverlay()](#getOverlay--) | Diğer grafik öğelerinin lejandla çakışmasına izin verilip verilmeyeceğini belirler. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Diğer grafik öğelerinin lejandla çakışmasına izin verilip verilmeyeceğini belirler. |
| [getPosition()](#getPosition--) | Grafikte lejandın konumunu belirtir. |
| [setPosition(int value)](#setPosition-int-) | Grafikte lejandın konumunu belirtir. |
| [getFormat()](#getFormat--) | Lejantın biçimini döndürür. |
| [getEntries()](#getEntries--) | Lejant girişlerini alır. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Diğer grafik öğelerinin lejandla çakışmasına izin verilip verilmeyeceğini belirler. Okunabilir/Yazılabilir boolean.

**Döndürür:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Diğer grafik öğelerinin lejandla çakışmasına izin verilip verilmeyeceğini belirler. Okunabilir/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Grafikte lejandın konumunu belirtir. X, Y, Width, Heigt özelliklerinin NaN olmayan değerleri bu özelliğin etkisini geçersiz kılar. Okunabilir/Yazılabilir [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Döndürür:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Grafikte lejandın konumunu belirtir. X, Y, Width, Heigt özelliklerinin NaN olmayan değerleri bu özelliğin etkisini geçersiz kılar. Okunabilir/Yazılabilir [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Lejantın biçimini döndürür. Salt-okunur [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

Lejant girişlerini alır. Salt-okunur [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Döndürür:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)