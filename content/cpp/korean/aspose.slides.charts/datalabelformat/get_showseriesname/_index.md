---
title: get_ShowSeriesName()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 차트의 데이터 레이블에 대한 시리즈 이름 표시 동작을 나타내는 Boolean을 반환합니다. True이면 시리즈 이름을 표시하고, False이면 숨깁니다. bool를 읽습니다.
type: docs
weight: 170
url: /ko/aspose.slides.charts/datalabelformat/get_showseriesname/
---
## DataLabelFormat::get_ShowSeriesName() 메서드

Returns a Boolean to indicate the series name display behavior for the data labels on a chart. True to show the series name. False to hide. Read **bool**.

```cpp
bool Aspose::Slides::Charts::DataLabelFormat::get_ShowSeriesName() override
```

## 비고

If parent of this [DataLabelFormat](../) object is a [DataLabelCollection](../../datalabelcollection/) collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the [DataLabelCollection](../../datalabelcollection/) collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the [DataLabelCollection](../../datalabelcollection/) collection (i.e. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" cause to all DataLabels[i].ShowSeriesName is equal to val).

## 참고

* 클래스 [DataLabelFormat](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)