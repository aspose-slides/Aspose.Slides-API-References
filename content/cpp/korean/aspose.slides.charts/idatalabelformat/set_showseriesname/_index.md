---
title: set_ShowSeriesName()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 차트의 데이터 레이블에 대한 시리즈 이름 표시 동작을 나타내는 Boolean 값을 설정합니다. 시리즈 이름을 표시하려면 true, 숨기려면 false를 사용합니다. bool을 기록합니다.
type: docs
weight: 183
url: /ko/aspose.slides.charts/idatalabelformat/set_showseriesname/
---
## IDataLabelFormat::set_ShowSeriesName(bool) 메서드

Sets a Boolean to indicate the series name display behavior for the data labels on a chart. True to show the series name. False to hide. Write **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowSeriesName(bool value)=0
```

## 비고

If parent of this [DataLabelFormat](../../datalabelformat/) object is a [DataLabelCollection](../../datalabelcollection/) collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the [DataLabelCollection](../../datalabelcollection/) collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the [DataLabelCollection](../../datalabelcollection/) collection (i.e. \"DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;\" cause to all DataLabels[i].ShowSeriesName is equal to val). 

## 참조

* 클래스 [IDataLabelFormat](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)