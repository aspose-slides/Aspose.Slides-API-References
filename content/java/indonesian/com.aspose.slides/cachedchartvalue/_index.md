---
title: CachedChartValue
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili nilai chart yang di-cache, mis. X, Y, ukuran gelembung, atau nilai utama.
type: docs
url: /id/com.aspose.slides/cachedchartvalue/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

Mewakili nilai chart yang di-cache (mis., X, Y, ukuran gelembung, atau nilai utama).
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [toString()](#toString--) | Mengembalikan representasi string dari nilai yang di-cache. |
| [toDouble()](#toDouble--) | Mengonversi nilai yang di-cache menjadi double. |
| [getData()](#getData--) | Mendapatkan objek data yang di-cache. |
### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```


### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string dari nilai yang di-cache.

**Mengembalikan:**
java.lang.String
### toDouble() {#toDouble--}
```
public final double toDouble()
```


Mengonversi nilai yang di-cache menjadi double.

**Mengembalikan:**
double - Representasi numerik, atau Double.NaN jika Data (\#getData.getData/\#setData(Object).setData(Object)) bernilai null atau tidak dapat dikonversi menjadi double.
### getData() {#getData--}
```
public final Object getData()
```


Mendapatkan objek data yang di-cache. Hanya-baca  Object .

**Mengembalikan:**
java.lang.Object