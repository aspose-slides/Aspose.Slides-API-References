---
title: ChartDataPointLevelsManager
second_title: Aspose.Slides Android용 Java API 레퍼런스
description: 데이터 포인트 레벨의 컨테이너입니다.
type: docs
url: /ko/com.aspose.slides/chartdatapointlevelsmanager/
---
**상속:**
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**
[com.aspose.slides.IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
```
public class ChartDataPointLevelsManager extends DomObject<ChartDataPoint> implements IChartDataPointLevelsManager
```

데이터 포인트 레벨의 컨테이너입니다. Treeamp 및 Sunburst 시리즈에 적용됩니다. 데이터 포인트 레벨 인덱스는 0부터 시작합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 정의된 레벨에 대한 IChartDataPointLevel 객체를 반환합니다. |
| [getCount()](#getCount--) | 데이터 포인트 레벨 수를 반환합니다. |
### get_Item(int level) {#get-Item-int-}
```
public final IChartDataPointLevel get_Item(int level)
```

정의된 레벨에 대한 IChartDataPointLevel 객체를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| level | int |  |

**반환값:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public final int getCount()
```

데이터 포인트 레벨 수를 반환합니다.

**반환값:**
int