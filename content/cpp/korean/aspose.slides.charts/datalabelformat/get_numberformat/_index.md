---
title: get_NumberFormat()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "DataLabels 개체에 대한 형식 문자열을 나타냅니다. System::String을 읽어 보세요."
type: docs
weight: 27
url: /ko/aspose.slides.charts/datalabelformat/get_numberformat/
---
## DataLabelFormat::get_NumberFormat() 메서드

DataLabels 개체에 대한 형식 문자열을 나타냅니다. 읽어 보세요 [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_NumberFormat() override
```

## 참고

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

이 [DataLabelFormat](../) 객체의 상위가 데이터 레이블의 [DataLabelCollection](../../datalabelcollection/) 컬렉션인 경우, 이 속성은 [DataLabelCollection](../../datalabelcollection/) 컬렉션에 있는 새 데이터 레이블에 대한 NumberFormat 속성의 기본값을 가져오거나 설정합니다. 이 속성에 값을 설정하면, 해당 값이 [DataLabelCollection](../../datalabelcollection/) 컬렉션에 있는 모든 데이터 레이블의 NumberFormat 속성에도 설정됩니다(예: "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" 은 모든 DataLabels[i].NumberFormat이 val과 동일해지게 합니다).

## 관련 항목

* 클래스 [String](../../../system/string/)
* 클래스 [DataLabelFormat](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)