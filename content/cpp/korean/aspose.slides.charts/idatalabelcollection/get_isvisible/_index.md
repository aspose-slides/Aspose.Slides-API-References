---
title: get_IsVisible()
second_title: Aspose.Slides C++ API 레퍼런스
description: False는 데이터 레이블이 기본적으로 표시되지 않음을 의미합니다 (따라서 DefaultDataLabelFormat 속성의 모든 Show*-flags(ShowValue, ...)가 false입니다). 읽기 전용 bool.
type: docs
weight: 27
url: /ko/aspose.slides.charts/idatalabelcollection/get_isvisible/
---
## IDataLabelCollection::get_IsVisible() 메서드


False는 데이터 레이블이 기본적으로 표시되지 않음을 의미합니다 (따라서 DefaultDataLabelFormat 속성의 모든 Show*-flags(ShowValue, ...)가 false입니다). 읽기 전용 **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelCollection::get_IsVisible()=0
```

## 비고


데이터 레이블이 기본적으로 표시되는 경우, [Hide()](../hide/) 메서드를 사용하여 기본적으로 숨길 수 있습니다. 그러나 데이터 레이블이 기본적으로 표시되지 않는 경우 (IsVisible는 false) Show*-flags(ShowValue, ...)를 true 상태로 설정하여 DefaultDataLabelFormat 속성을 통해 데이터 레이블을 \"기본적으로 표시 
by default\" 로 만들 수 있습니다.
## 참고

* 클래스 [IDataLabelCollection](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)