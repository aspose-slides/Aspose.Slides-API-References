---
title: IsStringLiteral
second_title: Aspose.Slides for C++ API 레퍼런스
description: 템플릿 매직을 사용하여 타입이 문자열 리터럴인지 확인합니다.
type: docs
weight: 1730
url: /ko/system/isstringliteral/
---
## IsStringLiteral 구조체

템플릿 매직을 사용하여 타입이 문자열 리터럴인지 확인합니다.

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 검사된 타입. |
| CharT | 확인할 문자 형식. |

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)