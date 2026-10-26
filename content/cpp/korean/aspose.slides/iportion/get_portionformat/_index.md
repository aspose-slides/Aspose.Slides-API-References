---
title: get_PortionFormat()
second_title: Aspose.Slides C++ API 레퍼런스
description: 상속이 적용되지 않은 텍스트 부분에 대해 명시적으로 설정된 서식 속성을 포함하는 서식 개체를 반환합니다. 읽기 전용 IPortionFormat.
type: docs
weight: 1
url: /ko/aspose.slides/iportion/get_portionformat/
---
## IPortion::get_PortionFormat() 메서드

상속이 적용되지 않은 텍스트 부분에 대해 명시적으로 설정된 서식 속성을 포함하는 서식 개체를 반환합니다. 읽기 전용 [IPortionFormat](../../iportionformat/).

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::IPortion::get_PortionFormat()=0
```

## 비고

서식 개체는 현재 부분에 대해서만 정의된 서식 매개변수를 포함하며, 상속된 데이터는 적용되지 않습니다.

상속된 값을 포함한 실제 값을 얻으려면 [IPortionFormat::GetEffective](../../iportionformat/geteffective/) 메서드를 사용하십시오.

## 또 보기

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPortionFormat](../../iportionformat/)
* 클래스 [IPortion](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)