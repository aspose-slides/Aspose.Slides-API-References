---
title: IActualLayout
second_title: Aspose.Slides for Java API Reference
description: Menentukan posisi aktual elemen diagram.
type: docs
url: /id/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Menentukan posisi aktual elemen diagram.
## Methods

| Method | Description |
| --- | --- |
| [getActualX()](#getActualX--) | Menentukan posisi x aktual (kiri) dari elemen diagram relatif terhadap sudut kiri atas diagram. |
| [getActualY()](#getActualY--) | Menentukan posisi atas aktual dari elemen diagram relatif terhadap sudut kiri atas diagram. |
| [getActualWidth()](#getActualWidth--) | Menentukan lebar aktual elemen diagram. |
| [getActualHeight()](#getActualHeight--) | Menentukan tinggi aktual elemen diagram. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```


Menentukan posisi x aktual (kiri) dari elemen diagram relatif terhadap sudut kiri atas diagram. Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk memperoleh nilai aktual. Baca float.

**Mengembalikan:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```


Menentukan posisi atas aktual dari elemen diagram relatif terhadap sudut kiri atas diagram. Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk memperoleh nilai aktual. Baca float.

**Mengembalikan:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```


Menentukan lebar aktual elemen diagram. Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk memperoleh nilai aktual. Baca float.

**Mengembalikan:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```


Menentukan tinggi aktual elemen diagram. Panggil metode IChart.ValidateChartLayout() terlebih dahulu untuk memperoleh nilai aktual. Baca float.

**Mengembalikan:**
float