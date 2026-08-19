---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Java Referensi API
description: Kontainer level data point.
type: docs
url: /id/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Kontainer level data point. Diterapkan untuk seri Treeamp dan Sunburst. Pengindeksan level data point dimulai dari nol.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Mengembalikan objek IChartDataPointLevel untuk level yang ditentukan. |
| [getCount()](#getCount--) | Mengembalikan jumlah level data point. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```

Mengembalikan objek IChartDataPointLevel untuk level yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| level | int |  |

**Mengembalikan:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Mengembalikan jumlah level data point.

**Mengembalikan:**
int