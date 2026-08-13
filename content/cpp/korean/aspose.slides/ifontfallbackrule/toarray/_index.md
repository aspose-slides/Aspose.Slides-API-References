---
title: ToArray()
second_title: Aspose.Slides for C++ API 참조
description: 이 규칙에 대한 모든 FallBack 글꼴을 포함하는 배열을 생성하고 반환합니다.
type: docs
weight: 105
url: /ko/aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() 메서드


이 규칙에 대한 모든 대체(FallBack) 글꼴을 포함하는 배열을 생성하고 반환합니다.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```


### 반환값

배열 [System::String](../../../system/string/)
## 비고



```cpp
// 폰트 목록을 포함하는 규칙을 생성합니다.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// 모든 폰트 이름을 배열로 가져옵니다
ArrayPtr<String> fontNames = newRule->ToArray();
```


## IFontFallBackRule::ToArray(int32_t, int32_t) 메서드


지정된 범위의 대체(FallBack) 글꼴을 포함하는 배열을 생성하고 반환합니다.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| startIndex | **int32_t** | 추가할 첫 번째 글꼴의 인덱스입니다. |
| count | **int32_t** | 추가할 글꼴의 수입니다. |

### 반환값

배열 [System::String](../../../system/string/)
## 비고



```cpp
// 폰트 목록을 포함하는 규칙을 생성합니다.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//마지막 두 개의 폰트 이름을 배열로 가져옵니다
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```


## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [IFontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)