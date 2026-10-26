---
title: IsStringByteSequence
second_title: Aspose.Slides for C++ API 레퍼런스
description: 타입이 문자열 문자 시퀀스인지 확인하는 템플릿 마법입니다.
type: docs
weight: 1717
url: /ko/system/isstringbytesequence/
---
## IsStringByteSequence struct


타입이 문자열 문자 시퀀스인지 확인하는 템플릿 마법입니다.

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 검사된 타입. |
| CharT | 대상이 되는 문자 타입. |

## 관련 항목

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)