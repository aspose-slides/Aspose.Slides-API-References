---
title: RemoveScriptFont()
second_title: Aspose.Slides C++ API 참조
description: 특정 스크립트 태그와 연관된 글꼴 설정을 테마의 글꼴 컬렉션에서 제거합니다.
type: docs
weight: 118
url: /ko/aspose.slides/fonts/removescriptfont/
---
## Fonts::RemoveScriptFont(System::String) 메서드

특정 스크립트 태그와 연관된 글꼴 설정을 테마의 글꼴 컬렉션에서 제거합니다.

```cpp
void Aspose::Slides::Fonts::RemoveScriptFont(System::String script) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | 제거해야 할 글꼴 설정이 적용된 BCP-47 스크립트 코드입니다. |
## 비고

이 예제는 히브리어 스크립트에 대한 글꼴 매핑을 제거하는 방법을 보여줍니다:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [Fonts](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)