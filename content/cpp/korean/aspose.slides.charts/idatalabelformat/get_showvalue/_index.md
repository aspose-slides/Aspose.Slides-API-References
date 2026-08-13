---
title: get_ShowValue()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. True는 백분율 값을 표시합니다. False는 숨깁니다. 읽기 bool.
type: docs
weight: 118
url: /ko/aspose.slides.charts/idatalabelformat/get_showvalue/
---
## IDataLabelFormat::get_ShowValue() 메서드


지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. True는 백분율 값을 표시합니다. False는 숨깁니다. 읽기 **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowValue()=0
```

## 비고


If parent of this [DataLabelFormat](../../datalabelformat/) object is a [DataLabelCollection](../../datalabelcollection/) collection of data labels then this 속성 gets or sets the default value of the ShowValue 속성 for the new data labels in the [DataLabelCollection](../../datalabelcollection/) collection. Set this 속성 with value also sets this value to the ShowValue 속성 for all data labels in the [DataLabelCollection](../../datalabelcollection/) collection (i.e. \"DataLabels.DefaultDataLabelFormat.ShowValue = val;\" cause to all DataLabels[i].ShowValue is equal to val). 



## 참조

* 클래스 [IDataLabelFormat](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)