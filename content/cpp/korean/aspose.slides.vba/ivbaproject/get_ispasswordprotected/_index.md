---
title: get_IsPasswordProtected()
second_title: Aspose.Slides for C++ API 레퍼런스
description: VBAProject가 프로젝트 속성을 보려면 비밀번호로 보호되는지 여부를 나타냅니다. 읽기 전용 bool.
type: docs
weight: 40
url: /ko/aspose.slides.vba/ivbaproject/get_ispasswordprotected/
---
## IVbaProject::get_IsPasswordProtected() 메서드

VBAProject가 프로젝트 속성을 보려면 비밀번호로 보호되는지 여부를 나타냅니다. 읽기 전용 **bool**.

```cpp
virtual bool Aspose::Slides::Vba::IVbaProject::get_IsPasswordProtected()=0
```

## 비고



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## 참조

* 클래스 [IVbaProject](../)
* 네임스페이스 [Aspose::Slides::Vba](../../)
* 라이브러리 [Aspose.Slides](../../../)