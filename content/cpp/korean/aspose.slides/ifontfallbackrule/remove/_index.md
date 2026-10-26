---
title: Remove()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 목록에서 특정 FallBack 글꼴의 첫 번째 항목을 제거합니다.
type: docs
weight: 79
url: /ko/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule::Remove(System::String) method

목록에서 특정 FallBack 글꼴의 첫 번째 항목을 제거합니다.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::Remove(System::String fontName)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | 목록에서 제거할 글꼴 이름입니다. |
## 비고

```cpp
// 글꼴 목록을 포함하는 규칙을 생성합니다.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//목록에서 Tahoma를 제거합니다.
newRule->Remove(u"Tahoma");
```

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [IFontFallBackRule](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)