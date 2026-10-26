---
title: IsExceptionWrapper
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 유형이 Exception 클래스이거나 그 파생 클래스인지 판단하는 템플릿 프레디케이트.
type: docs
weight: 1678
url: /ko/system/isexceptionwrapper/
---
## IsExceptionWrapper 구조체

지정된 유형이 Exception 클래스이거나 그 파생 클래스인지 판단하는 템플릿 프레디케이트.

```cpp
template<typename T>class IsExceptionWrapper : public std::is_base_of<System::ExceptionWrapperType, T>
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 확인할 유형 |

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)