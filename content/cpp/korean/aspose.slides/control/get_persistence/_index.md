---
title: get_Persistence()
second_title: Aspose.Slides for C++ API 레퍼런스
description: ActiveX 컨트롤의 속성을 저장하는 데 사용되는 메서드를 가져옵니다. 읽기 전용 PersistenceType.
type: docs
weight: 1
url: /ko/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() 메서드

ActiveX 컨트롤의 속성을 저장하는 데 사용되는 메서드를 가져옵니다. 읽기 전용 [PersistenceType](../../persistencetype/).

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## 비고

다음 예제는 Persistence 속성을 사용하여 ActiveX 개체의 속성을 XML 기반 ActiveX 속성으로 변경할 수 있는지 확인하는 방법을 보여줍니다:
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // ActiveX 속성을 바이너리 파일에 저장된 형태로 관리하기 위해 자신만의 메서드를 사용하십시오
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## 참고

* 열거형 [PersistenceType](../../persistencetype/)
* 클래스 [Control](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)