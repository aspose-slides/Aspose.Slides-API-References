---
title: ILegendEntryCollection
second_title: Aspose.Slides for Android via Java API 레퍼런스
description: 범례 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

범례 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 이 목록에 있는 차트 유형인 ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie인 경우 Chart.ChartData.Series[0].DataPoints[index]에 해당하는 범례 항목의 속성을 가져옵니다; 또는 다른 차트 유형에 대해서는 Chart.ChartData.Series[index]에 해당합니다. |
| [getCount()](#getCount--) | 컬렉션에 실제로 포함된 요소의 수를 가져옵니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

이 목록에 있는 차트 유형인 ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie인 경우 Chart.ChartData.Series[0].DataPoints[index]에 해당하는 범례 항목의 속성을 가져옵니다; 또는 다른 차트 유형에 대해서는 Chart.ChartData.Series[index]에 해당합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```

컬렉션에 실제로 포함된 요소의 수를 가져옵니다. 읽기 전용 int.

**반환값:**
int