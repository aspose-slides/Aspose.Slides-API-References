---
title: GetHashCode()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 비교 옵션을 기반으로 문자열 해시 코드를 가져옵니다.
type: docs
weight: 144
url: /ko/system.globalization/compareinfo/gethashcode/
---
## CompareInfo::GetHashCode(const String\&, CompareOptions) const 메서드

지정된 비교 옵션을 기반으로 문자열 해시 코드를 가져옵니다.

```cpp
virtual int System::Globalization::CompareInfo::GetHashCode(const String &value, CompareOptions options) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 입력 문자열. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) 비교 옵션. |

### 반환값

해시 코드.

## CompareInfo::GetHashCode() const 메서드

C# [Object.GetHashCode()](../../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 개체의 해싱을 가능하게 합니다.

```cpp
int System::Globalization::CompareInfo::GetHashCode() const override
```

### 반환값

해당 클래스에서 계산된 해시 코드 값.

## 또 참조

* Enum [CompareOptions](../../compareoptions/)
* Class [String](../../../system/string/)
* Class [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)