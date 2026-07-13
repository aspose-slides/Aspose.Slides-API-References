---
title: IActualLayout
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies actual position of a chart element.
type: docs
url: /id/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Menentukan posisi aktual elemen diagram.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getActualX()](#getActualX--) | Menentukan lokasi x aktual (kiri) elemen diagram relatif terhadap sudut kiri atas diagram. |
| [getActualY()](#getActualY--) | Menentukan posisi atas aktual elemen diagram relatif terhadap sudut kiri atas diagram. |
| [getActualWidth()](#getActualWidth--) | Menentukan lebar aktual elemen diagram. |
| [getActualHeight()](#getActualHeight--) | Menentukan tinggi aktual elemen diagram. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```


Menentukan lokasi x aktual (kiri) elemen diagram relatif terhadap sudut kiri atas diagram. Call method IChart.ValidateChartLayout() before to get actual values. Read float.

**Mengembalikan:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```


Menentukan posisi atas aktual elemen diagram relatif terhadap sudut kiri atas diagram. Call method IChart.ValidateChartLayout() before to get actual values. Read float.

**Mengembalikan:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```


Menentukan lebar aktual elemen diagram. Call method IChart.ValidateChartLayout() before to get actual values. Read float.

**Mengembalikan:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```


Menentukan tinggi aktual elemen diagram. Call method IChart.ValidateChartLayout() before to get actual values. Read float.

**Mengembalikan:**
float