---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Container of data point levels.
type: docs
url: /pl/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

Kontener poziomów punktów danych. Stosowany dla serii Treeamp i Sunburst. Indeksowanie poziomów punktów danych zaczyna się od zera.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Zwraca obiekt IChartDataPointLevel dla określonego poziomu. |
| [getCount()](#getCount--) | Zwraca liczbę poziomów punktów danych. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```

Zwraca obiekt IChartDataPointLevel dla określonego poziomu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| level | int |  |

**Zwraca:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Zwraca liczbę poziomów punktów danych.

**Zwraca:**
int