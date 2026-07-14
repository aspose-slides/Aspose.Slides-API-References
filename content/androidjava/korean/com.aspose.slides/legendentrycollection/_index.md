---
title: LegendEntryCollection
second_title: Java API를 통한 Android용 Aspose.Slides
description: 범례 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/legendentrycollection/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)  
```
public class LegendEntryCollection implements ILegendEntryCollection
```

범례 컬렉션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 차트 유형이 다음 목록에 있는 경우 Chart.ChartData.Series[0].DataPoints[index]에 해당하는 범례 항목의 속성을 가져옵니다: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; 또는 다른 차트 유형에 대해서는 Chart.ChartData.Series[index]에 해당합니다. |
| [getCount()](#getCount--) | 범례 항목의 수를 가져옵니다. |

### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```

Chart.ChartData.Series[0].DataPoints[index]에 해당하는 범례 항목의 속성을 가져옵니다: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; 또는 다른 차트 유형에 대해서는 Chart.ChartData.Series[index]에 해당합니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getCount() {#getCount--}
```
public final int getCount()
```

범례 항목의 수를 가져옵니다. 읽기 전용 int.

**반환값:**  
int