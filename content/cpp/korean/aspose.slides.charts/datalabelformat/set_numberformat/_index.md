---
title: set_NumberFormat()
second_title: Aspose.Slides for C++ API 참조
description: "DataLabels 객체의 형식 문자열을 나타냅니다. System::String을 씁니다."
type: docs
weight: 40
url: /ko/aspose.slides.charts/datalabelformat/set_numberformat/
---
## DataLabelFormat::set_NumberFormat(System::String) 메서드


DataLabels 객체의 형식 문자열을 나타냅니다. [System::String](../../../system/string/)를 씁니다.

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_NumberFormat(System::String value) override
```

## 비고



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





이 [DataLabelFormat](../) 객체의 부모가 [DataLabelCollection](../../datalabelcollection/) 데이터 레이블 컬렉션인 경우, 이 속성은 [DataLabelCollection](../../datalabelcollection/) 컬렉션에 있는 새 데이터 레이블에 대한 NumberFormat 속성의 기본 값을 가져오거나 설정합니다. 이 속성을 값으로 설정하면 그 값이 [DataLabelCollection](../../datalabelcollection/) 컬렉션에 있는 모든 데이터 레이블의 NumberFormat 속성에도 설정됩니다 (예: "DataLabels.DefaultDataLabelFormat.NumberFormat = val;"은 모든 DataLabels[i].NumberFormat이 val와 동일하게 됩니다). 



## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [DataLabelFormat](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)