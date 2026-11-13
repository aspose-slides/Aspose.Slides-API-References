---
title: ICachedChartValue
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili nilai chart yang di-cache, misalnya X, Y, ukuran gelembung, atau nilai utama.
type: docs
url: /id/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

Mewakili nilai chart yang di-cache (mis., X, Y, ukuran gelembung, atau nilai utama).
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getData()](#getData--) | Gets the cached data object. |
| [toDouble()](#toDouble--) | Converts the cached value to a double. |
### getData() {#getData--}
```
public abstract Object getData()
```

Mendapatkan objek data yang di-cache. Hanya-baca  Object .

**Mengembalikan:**
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Mengonversi nilai yang di-cache ke double.

**Mengembalikan:**
double - The numeric representation, or Double.NaN if Data (\#getData.getData) is null or cannot be converted to a double.