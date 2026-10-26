---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: 데이터 포인트 레벨의 컨테이너입니다.
type: docs
url: /ko/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

데이터 포인트 레벨의 컨테이너입니다. Treeamp 및 Sunburst 시리즈에 적용됩니다. 데이터 포인트 레벨 인덱싱은 0부터 시작합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 정의된 레벨에 대한 IChartDataPointLevel 객체를 반환합니다. |
| [getCount()](#getCount--) | 데이터 포인트 레벨 수를 반환합니다. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```

정의된 레벨에 대한 IChartDataPointLevel 객체를 반환합니다.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| level | int |  |

**반환값:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public abstract int getCount()
```

데이터 포인트 레벨 수를 반환합니다.

**반환값:**
int