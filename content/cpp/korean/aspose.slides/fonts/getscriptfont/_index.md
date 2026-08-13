---
title: GetScriptFont()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션 테마에서 특정 스크립트 태그와 연결된 글꼴 이름을 가져옵니다.
type: docs
weight: 92
url: /ko/aspose.slides/fonts/getscriptfont/
---
## Fonts::GetScriptFont(System::String) 메서드


프레젠테이션 테마에서 특정 스크립트 태그와 연결된 글꼴 이름을 가져옵니다.

```cpp
System::String Aspose::Slides::Fonts::GetScriptFont(System::String script) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | BCP-47 스크립트 코드(예: \"Latn\", \"Cyrl\", \"Jpan\")는 쓰기 시스템을 식별하는 데 사용됩니다. |

### 반환값

지정된 스크립트에 사용되는 글꼴 이름을 반환하며, 스크립트가 정의되지 않은 경우 **null**을 반환합니다.
## 비고



이 예제에서는 프레젠테이션 테마에서 Cyrillic 스크립트에 할당된 글꼴을 검색하는 방법을 보여줍니다. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## 또 보기

* 클래스 [String](../../../system/string/)
* 클래스 [Fonts](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)