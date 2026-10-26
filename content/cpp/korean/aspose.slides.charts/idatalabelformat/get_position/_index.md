---
title: get_Position()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 데이터 레이블의 위치를 나타냅니다. LegendDataLabelPosition을 읽으십시오.
type: docs
weight: 66
url: /ko/aspose.slides.charts/idatalabelformat/get_position/
---
## IDataLabelFormat::get_Position() 메서드

데이터 레이블의 위치를 나타냅니다. [LegendDataLabelPosition](../../legenddatalabelposition/)를 읽으십시오.

```cpp
virtual LegendDataLabelPosition Aspose::Slides::Charts::IDataLabelFormat::get_Position()=0
```

## 비고

이 [DataLabelFormat](../../datalabelformat/) 객체의 상위가 [DataLabelCollection](../../datalabelcollection/) 데이터 레이블 컬렉션인 경우, 이 속성은 [DataLabelCollection](../../datalabelcollection/) 컬렉션에 있는 새 데이터 레이블에 대한 Position 속성의 기본값을 가져오거나 설정합니다. [DataLabel](../../datalabel/) 객체의 위치를 나타냅니다. 이 속성을 값으로 설정하면 [DataLabelCollection](../../datalabelcollection/) 컬렉션에 있는 모든 데이터 레이블의 Position 속성에도 동일한 값이 설정됩니다 (예: "DataLabels.DefaultDataLabelFormat.Position = val;" 은 모든 DataLabels[i].Position이 val과 같아지도록 합니다).

## 참고

* 열거형 [LegendDataLabelPosition](../../legenddatalabelposition/)
* 클래스 [IDataLabelFormat](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)