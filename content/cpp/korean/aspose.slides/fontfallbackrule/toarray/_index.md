---
title: ToArray()
second_title: C++용 Aspose.Slides API 참조
description: 이 규칙에 대한 모든 대체 폰트를 포함하는 배열을 생성하고 반환합니다.
type: docs
weight: 144
url: /ko/aspose.slides/fontfallbackrule/toarray/
---
## FontFallBackRule::ToArray() 메서드

이 규칙에 대한 모든 대체 폰트를 포함하는 배열을 생성하고 반환합니다.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray() override
```

### 반환값

배열 [System::String](../../../system/string/)

## 비고

```cpp
// 글꼴 목록을 포함하는 규칙을 생성합니다.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// 모든 글꼴 이름을 배열로 가져옵니다.
ArrayPtr<String> fontNames = newRule->ToArray();
```

## FontFallBackRule::ToArray(int32_t, int32_t) 메서드

목록에서 지정된 범위의 모든 대체 폰트를 포함하는 배열을 생성하고 반환합니다.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray(int32_t startIndex, int32_t count) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| startIndex | **int32_t** | 추가할 첫 번째 폰트의 인덱스입니다. |
| count | **int32_t** | 추가할 폰트 수입니다. |

### 반환값

배열 [System::String](../../../system/string/)

## 비고

```cpp
// 글꼴 목록을 포함하는 규칙을 생성합니다.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// 마지막 두 글꼴 이름을 배열로 가져옵니다.
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## 참조

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [FontFallBackRule](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)