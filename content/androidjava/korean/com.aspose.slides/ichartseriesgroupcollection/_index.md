---
title: IChartSeriesGroupCollection
second_title: Aspose.Slides for Android Java API 레퍼런스
description: 결합 가능한 시리즈 그룹의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ichartseriesgroupcollection/
---
**구현된 모든 인터페이스:**  
com.aspose.slides.IGenericCollection  
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

구성 가능한 시리즈 그룹의 컬렉션을 나타냅니다.

--------------------

1) 각 시리즈 그룹은 결합 가능한 유형의 시리즈를 포함합니다. 결합 가능한 시리즈 유형 그룹은 CombinableSeriesTypesGroup 열거형으로 정의 및 설명됩니다. 또한 각 시리즈 그룹은 기본 축에 플롯되거나 보조 축에 플롯되는 시리즈를 포함합니다(하나의 그룹에 두 경우가 모두 포함되지는 않음). 따라서 시리즈 그룹화 원칙은 앞에서 언급한 유형 그룹과 기본/보조 플롯 유형에 따라 그룹화하는 것입니다.  
2) 시리즈 그룹은 그룹 내 각 시리즈에 공통적인 일부 시리즈 속성(「시리즈 그룹 속성」)을 포함합니다. ChartSeriesGroup 클래스의 「시리즈 그룹 속성」은 읽기/쓰기가 가능합니다. 각 「시리즈 그룹 속성」은 ChartSeries 클래스에서 읽기 전용 투영으로 제공될 수 있습니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | 시리즈를 기준으로 시리즈 그룹을 가져옵니다. |
| [get_Item(int index)](#get-Item-int-) | 인덱스를 기준으로 시리즈 그룹을 가져옵니다. |

### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```

시리즈를 기준으로 시리즈 그룹을 가져옵니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**반환값:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```

인덱스를 기준으로 시리즈 그룹을 가져옵니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)