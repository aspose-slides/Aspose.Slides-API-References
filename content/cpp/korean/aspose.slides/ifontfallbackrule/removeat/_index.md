---
title: RemoveAt()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 목록에서 지정된 인덱스에 있는 FallBack 글꼴을 제거합니다.
type: docs
weight: 92
url: /ko/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule::RemoveAt(int32_t) 메서드

목록에서 지정된 인덱스에 있는 FallBack 글꼴을 제거합니다.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::RemoveAt(int32_t index)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 제거할 글꼴의 0 기반 인덱스입니다. |
## 비고



```cpp
// 글꼴 목록을 포함하는 규칙을 생성합니다.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// 목록에서 Tahoma를 제거합니다.
newRule->RemoveAt(2);
```

## 참조

* 클래스 [IFontFallBackRule](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)