---
title: get_LinkPathRelative()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "링크된 파일이 있으면 해당 파일의 상대 경로를 반환하고, 없으면 빈 문자열을 반환합니다. 읽기 전용 System::String."
type: docs
weight: 131
url: /ko/aspose.slides/oleobjectframe/get_linkpathrelative/
---
## OleObjectFrame::get_LinkPathRelative() 메서드


링크된 파일이 있으면 해당 파일의 상대 경로를 반환하고, 없으면 빈 문자열을 반환합니다. 읽기 전용 [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::OleObjectFrame::get_LinkPathRelative() override
```

## 비고


Ppt 프레젠테이션에서 일부 Ole 개체 링크는 상대 경로를 가질 수 있습니다. 


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## 또한 보기

* 클래스 [String](../../../system/string/)
* 클래스 [OleObjectFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)