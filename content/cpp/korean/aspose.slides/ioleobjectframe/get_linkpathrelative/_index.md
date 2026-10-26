---
title: get_LinkPathRelative()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "존재하는 경우 연결된 파일에 대한 상대 경로를 반환하고, 그렇지 않으면 빈 문자열을 반환합니다. 읽기 전용 System::String."
type: docs
weight: 118
url: /ko/aspose.slides/ioleobjectframe/get_linkpathrelative/
---
## IOleObjectFrame::get_LinkPathRelative() 메서드

존재하는 경우 연결된 파일에 대한 상대 경로를 반환하고, 그렇지 않으면 빈 문자열을 반환합니다. 읽기 전용 [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::IOleObjectFrame::get_LinkPathRelative()=0
```

## 비고

Ppt 프레젠테이션에서 일부 Ole 객체 링크는 상대 경로로 표시될 수 있습니다.

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [IOleObjectFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)