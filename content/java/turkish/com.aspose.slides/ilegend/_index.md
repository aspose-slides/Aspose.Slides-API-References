---
title: ILegend
second_title: Aspose.Slides for Java API Referansı
description: Grafik efsanesinin özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/ilegend/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

Grafiğin efsane (legend) özelliklerini temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getOverlay()](#getOverlay--) | Diğer grafik öğelerinin efsanenin üzerine yazmasına izin verilip verilmeyeceğini belirler. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Diğer grafik öğelerinin efsanenin üzerine yazmasına izin verilip verilmeyeceğini belirler. |
| [getPosition()](#getPosition--) | Efsanenin bir grafikteki konumunu belirtir. |
| [setPosition(int value)](#setPosition-int-) | Efsanenin bir grafikteki konumunu belirtir. |
| [getFormat()](#getFormat--) | Efsanenin biçimini döndürür. |
| [getEntries()](#getEntries--) | Efsane girişlerini alır. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


Diğer grafik öğelerinin efsanenin üzerine yazmasına izin verilip verilmeyeceğini belirler. Okunur/Yazılabilir boolean.

**Döndürür:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


Diğer grafik öğelerinin efsanenin üzerine yazmasına izin verilip verilmeyeceğini belirler. Okunur/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Efsanenin bir grafikteki konumunu belirtir. X, Y, Width, Height özelliklerinin NaN olmayan değerleri bu özelliğin etkisini geçersiz kılar. Okunur/Yazılabilir [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Döndürür:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Efsanenin bir grafikteki konumunu belirtir. X, Y, Width, Height özelliklerinin NaN olmayan değerleri bu özelliğin etkisini geçersiz kılar. Okunur/Yazılabilir [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Efsanenin biçimini döndürür. Salt okunur [IFormat](../../com.aspose.slides/iformat).

**Döndürür:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```


Efsane girişlerini alır. Salt okunur [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Döndürür:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)