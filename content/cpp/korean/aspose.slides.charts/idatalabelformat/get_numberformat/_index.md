---
title: get_NumberFormat()
second_title: Aspose.Slides C++용 API 참조
description: "DataLabels 객체의 형식 문자열을 나타냅니다. System::String을 읽으십시오."
type: docs
weight: 27
url: /ko/aspose.slides.charts/idatalabelformat/get_numberformat/
---
## IDataLabelFormat::get_NumberFormat() 메서드


DataLabels 객체의 형식 문자열을 나타냅니다. [System::String](../../../system/string/)을(를) 읽으십시오.

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_NumberFormat()=0
```

## 비고



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```



이 [DataLabelFormat](../../datalabelformat/) 객체의 상위가 [DataLabelCollection](../../datalabelcollection/) 데이터 레이블 컬렉션인 경우, 이 속성은 [DataLabelCollection](../../datalabelcollection/) 컬렉션에서 새로운 데이터 레이블에 대한 NumberFormat 속성의 기본 값을 가져오거나 설정합니다. 이 속성에 값을 설정하면 해당 값이 [DataLabelCollection](../../datalabelcollection/) 컬렉션의 모든 데이터 레이블에 대한 NumberFormat 속성에도 설정됩니다(예: \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" 은 모든 DataLabels[i].NumberFormat을 val와 동일하게 합니다). 
## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [IDataLabelFormat](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)