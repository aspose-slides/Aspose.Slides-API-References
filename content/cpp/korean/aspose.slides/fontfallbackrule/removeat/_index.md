---
title: RemoveAt()
second_title: Aspose.Slides C++ API 레퍼런스
description: 목록에서 지정된 인덱스에 있는 FallBack 글꼴을 제거합니다.
type: docs
weight: 131
url: /ko/aspose.slides/fontfallbackrule/removeat/
---
## FontFallBackRule::RemoveAt(int32_t) 메서드


Removes the FallBack font at the specified index of the list.

```cpp
void Aspose::Slides::FontFallBackRule::RemoveAt(int32_t index) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 제거할 글꼴의 0부터 시작하는 인덱스입니다. |
## 비고



```cpp
// 글꼴 목록을 포함하는 규칙을 생성합니다.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// 리스트에서 Tahoma를 제거합니다.
newRule->RemoveAt(2);
```


## 참고

* 클래스 [FontFallBackRule](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)