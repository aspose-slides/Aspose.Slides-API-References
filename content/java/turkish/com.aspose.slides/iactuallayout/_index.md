---
title: IActualLayout
second_title: Aspose.Slides for Java API Reference
description: Specifies actual position of a chart element.
type: docs
url: /tr/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Grafik öğesinin gerçek konumunu belirtir.
## Metotlar

| Method | Description |
| --- | --- |
| [getActualX()](#getActualX--) | Grafik öğesinin sol üst köşesine göre gerçek x konumunu (sol) belirtir. |
| [getActualY()](#getActualY--) | Grafik öğesinin sol üst köşesine göre gerçek üst konumunu belirtir. |
| [getActualWidth()](#getActualWidth--) | Grafik öğesinin gerçek genişliğini belirtir. |
| [getActualHeight()](#getActualHeight--) | Grafik öğesinin gerçek yüksekliğini belirtir. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```


Grafik öğesinin sol üst köşesine göre gerçek x konumunu (sol) belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() metodunu çağırın. Okunur float.

**Returns:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```


Grafik öğesinin sol üst köşesine göre gerçek üst konumunu belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() metodunu çağırın. Okunur float.

**Returns:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```


Grafik öğesinin gerçek genişliğini belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() metodunu çağırın. Okunur float.

**Returns:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```


Grafik öğesinin gerçek yüksekliğini belirtir. Gerçek değerleri almak için önce IChart.ValidateChartLayout() metodunu çağırın. Okunur float.

**Returns:**
float