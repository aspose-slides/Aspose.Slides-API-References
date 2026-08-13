---
title: SetScriptFont()
second_title: Aspose.Slides for C++ API 참조
description: 특정 스크립트 태그에 폰트 이름을 할당하며, 이 태그는 프레젠테이션에서 해당 스크립트 텍스트가 어떻게 렌더링되는지를 정의합니다.
type: docs
weight: 105
url: /ko/aspose.slides/fonts/setscriptfont/
---
## Fonts::SetScriptFont(System::String, System::String) 메서드

특정 스크립트 태그에 폰트 이름을 할당합니다. 이 태그는 프레젠테이션에서 해당 스크립트 텍스트가 어떻게 렌더링되는지를 정의합니다.

```cpp
void Aspose::Slides::Fonts::SetScriptFont(System::String script, System::String fontName) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | BCP-47 스크립트 코드(예: "Arab", "Hebr", "Hans")로, 쓰기 시스템을 식별합니다. |
| fontName | [System::String](../../../system/string/) | 지정된 스크립트에 할당할 폰트 이름입니다. |

## 비고

이 예제는 아랍어 스크립트의 폰트를 "Segoe UI"로 설정하는 방법을 보여줍니다:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [Fonts](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)