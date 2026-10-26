---
title: IndexOf()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션에서 지정된 규칙의 인덱스를 반환합니다.
type: docs
weight: 157
url: /ko/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule::IndexOf(System::String) 메서드

컬렉션에서 지정된 규칙의 인덱스를 반환합니다.

```cpp
int32_t Aspose::Slides::FontFallBackRule::IndexOf(System::String fontName) override
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | 찾을 폰트 이름. |

### Return Value

폰트의 인덱스이며, 목록에 폰트가 없으면 -1을 반환합니다.

## 비고

```cpp
// 글꼴 목록을 포함하는 규칙을 생성합니다.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Tahoma의 인덱스를 가져옵니다.
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [FontFallBackRule](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)