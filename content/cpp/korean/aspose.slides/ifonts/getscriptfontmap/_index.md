---
title: GetScriptFontMap()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션의 모든 스크립트 글꼴 정의를 사전 형태로 반환합니다.
type: docs
weight: 79
url: /ko/aspose.slides/ifonts/getscriptfontmap/
---
## IFonts::GetScriptFontMap() 메서드

프레젠테이션에 있는 모든 스크립트 글꼴 정의의 사전을 반환합니다.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::IFonts::GetScriptFontMap()=0
```

### 반환값

스크립트 코드와 글꼴 이름을 매핑하는 사전입니다.
## 비고

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IDictionary](../../../system.collections.generic/idictionary/)
* 클래스 [String](../../../system/string/)
* 클래스 [IFonts](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)