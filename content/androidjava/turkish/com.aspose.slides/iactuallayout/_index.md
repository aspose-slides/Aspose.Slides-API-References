---
title: IActualLayout
second_title: Aspose.Slides for Android via Java API Reference
description: Bir grafik öğesinin gerçek konumunu belirtir.
type: docs
url: /tr/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Bir grafik öğesinin gerçek konumunu belirtir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getActualX()](#getActualX--) | Grafik öğesinin sol üst köşeye göre gerçek x konumunu (sol) belirtir. |
| [getActualY()](#getActualY--) | Grafik öğesinin sol üst köşeye göre gerçek üst konumunu belirtir. |
| [getActualWidth()](#getActualWidth--) | Grafik öğesinin gerçek genişliğini belirtir. |
| [getActualHeight()](#getActualHeight--) | Grafik öğesinin gerçek yüksekliğini belirtir. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```

Grafik öğesinin sol üst köşeye göre gerçek x konumunu (sol) belirtir. Gerçek değerleri almak için IChart.ValidateChartLayout() metodunu önce çağırın. Okunur float.

**Döndürür:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```

Grafik öğesinin sol üst köşeye göre gerçek üst konumunu belirtir. Gerçek değerleri almak için IChart.ValidateChartLayout() metodunu önce çağırın. Okunur float.

**Döndürür:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```

Grafik öğesinin gerçek genişliğini belirtir. Gerçek değerleri almak için IChart.ValidateChartLayout() metodunu önce çağırın. Okunur float.

**Döndürür:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```

Grafik öğesinin gerçek yüksekliğini belirtir. Gerçek değerleri almak için IChart.ValidateChartLayout() metodunu önce çağırın. Okunur float.

**Döndürür:**
float