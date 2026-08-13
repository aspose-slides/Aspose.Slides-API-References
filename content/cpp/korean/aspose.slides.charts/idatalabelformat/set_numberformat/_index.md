---
title: set_NumberFormat()
second_title: Aspose.Slides for C++ API 참조
description: "DataLabels 개체에 대한 형식 문자열을 나타냅니다. System::String을 씁니다."
type: docs
weight: 40
url: /ko/aspose.slides.charts/idatalabelformat/set_numberformat/
---
## IDataLabelFormat::set_NumberFormat(System::String) method

DataLabels 개체에 대한 형식 문자열을 나타냅니다. [System::String](../../../system/string/)를 씁니다.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_NumberFormat(System::String value)=0
```

## 비고

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

이 [DataLabelFormat](../../datalabelformat/) 개체의 상위가 [DataLabelCollection](../../datalabelcollection/) 데이터 레이블 컬렉션인 경우, 이 속성은 [DataLabelCollection](../../datalabelcollection/) 컬렉션의 새 데이터 레이블에 대한 NumberFormat 속성의 기본값을 가져오거나 설정합니다. 이 속성을 값으로 설정하면 해당 값이 [DataLabelCollection](../../datalabelcollection/) 컬렉션의 모든 데이터 레이블에 대한 NumberFormat 속성에도 설정됩니다 (예: "DataLabels.DefaultDataLabelFormat.NumberFormat = val;"는 모든 DataLabels[i].NumberFormat이 val와 동일하게 됩니다).

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [IDataLabelFormat](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)