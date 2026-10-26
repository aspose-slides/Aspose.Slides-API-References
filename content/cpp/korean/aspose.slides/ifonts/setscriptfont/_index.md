---
title: SetScriptFont()
second_title: C++용 Aspose.Slides API 참조
description: 특정 스크립트 태그에 글꼴 이름을 할당하여 해당 스크립트의 텍스트가 프레젠테이션에서 어떻게 렌더링되는지를 정의합니다.
type: docs
weight: 105
url: /ko/aspose.slides/ifonts/setscriptfont/
---
## IFonts::SetScriptFont(System::String, System::String) 메서드


특정 스크립트 태그에 글꼴 이름을 할당하여 해당 스크립트 텍스트가 프레젠테이션에 어떻게 렌더링되는지를 정의합니다.

```cpp
virtual void Aspose::Slides::IFonts::SetScriptFont(System::String script, System::String fontName)=0
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | 쓰기 시스템을 식별하는 BCP-47 스크립트 코드 (예: \"Arab\", \"Hebr\", \"Hans\") |
| fontName | [System::String](../../../system/string/) | 지정된 스크립트에 할당할 글꼴 이름 |

## 비고

이 예제는 아라비아어 스크립트에 대한 글꼴을 \"Segoe UI\" 로 설정하는 방법을 보여줍니다: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [IFonts](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)