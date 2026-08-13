---
title: get_IsPasswordProtected()
second_title: Aspose.Slides C++ API 레퍼런스
description: VBAProject가 프로젝트 속성을 보기 위해 비밀번호로 보호되는지 여부를 나타냅니다. 읽기 전용 bool.
type: docs
weight: 40
url: /ko/aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() 메서드

VBAProject가 프로젝트 속성을 보기 위해 비밀번호로 보호되는지 여부를 나타냅니다. 읽기 전용 **bool**.

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
```

## 비고



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## 참고

* 클래스 [VbaProject](../)
* 네임스페이스 [Aspose::Slides::Vba](../../)
* 라이브러리 [Aspose.Slides](../../../)