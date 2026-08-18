---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Java API Referansı
description: Veri noktası seviyelerinin kapsayıcısı.
type: docs
url: /tr/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Veri noktası seviyelerinin kapsayıcısı. Treeamp ve Sunburst serileri için uygulanır. Veri noktası seviyeleri indekslemesi sıfır tabanlıdır.
## Methods

| Metod | Açıklama |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Tanımlı seviye için IChartDataPointLevel nesnesini döndürür. |
| [getCount()](#getCount--) | Veri noktası seviyelerinin sayısını döndürür. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```


Tanımlı seviye için IChartDataPointLevel nesnesini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| level | int |  |

**Döndürür:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Veri noktası seviyelerinin sayısını döndürür.

**Döndürür:**
int