---
title: get_ActiveXControlBinary()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 영속에 사용되는 메서드가 PersistStream, PersistStreamInit 또는 PersistStorage인 경우 ActiveX 컨트롤의 영속성을 지정합니다.
type: docs
weight: 118
url: /ko/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() 메서드

ActiveX 컨트롤의 영속성을 지정합니다. 영속에 사용되는 메서드가 PersistStream, PersistStreamInit 또는 PersistStorage인 경우.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## 비고

다음 예제는 ActiveX 속성을 변경하기 위해 ActiveXControlBinary 속성을 사용하는 방법을 보여줍니다:
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // 이진 파일에 저장된 ActiveX 속성을 관리하기 위해 자체 메서드를 사용하세요
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## 참고

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [Control](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)