---
title: IsStringPointer
second_title: Aspose.Slides C++ API 레퍼런스
description: 형식이 문자 문자열에 대한 포인터인지 확인하는 템플릿 매직.
type: docs
weight: 1743
url: /ko/system/isstringpointer/
---
## IsStringPointer 구조체

Template magic to check if a type is a pointer to character string.

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 검사된 타입. |
| CharT | 대상이 되는 문자 타입. |

## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)