---
title: GetScriptFont()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션 테마에서 특정 스크립트 태그와 연결된 글꼴 이름을 가져옵니다.
type: docs
weight: 92
url: /ko/aspose.slides/ifonts/getscriptfont/
---
## IFonts::GetScriptFont(System::String) 메서드

프레젠테이션 테마에서 특정 스크립트 태그와 연결된 글꼴 이름을 가져옵니다.

```cpp
virtual System::String Aspose::Slides::IFonts::GetScriptFont(System::String script)=0
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | 작성 시스템을 식별하기 위해 사용되는 BCP-47 스크립트 코드(예: "Latn", "Cyrl", "Jpan")입니다. |

### 반환 값

지정된 스크립트에 사용되는 글꼴 이름이며, 스크립트가 정의되지 않은 경우 **null**을 반환합니다.

## 비고



이 예제는 프레젠테이션 테마에서 키릴 문자 스크립트에 할당된 글꼴을 검색하는 방법을 보여줍니다.
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [IFonts](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)