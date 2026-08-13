---
title: AppendFormat()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 포맷된 문자열을 빌더에 추가합니다.
type: docs
weight: 131
url: /ko/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String\&, const TArgs\&...) 메서드

포맷된 문자열을 빌더에 추가합니다.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TArgs | 인수 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | 포맷 문자열. |
| args | const TArgs\&... | 포맷 문자열 위치에 삽입할 인수. |

### 반환 값

현재 포인터.

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>\&, const String\&, const TArgs\&...) 메서드

포맷된 문자열을 빌더에 추가합니다.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TArgs | 인수 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)\<[IFormatProvider](../../../system/iformatprovider/)\>\& | 포맷 공급자; 무시됩니다. |
| format | const [String](../../../system/string/)\& | 포맷 문자열. |
| args | const TArgs\&... | 포맷 문자열 위치에 삽입할 인수. |

### 반환 값

현재 포인터.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [StringBuilder](../)
* 클래스 [String](../../../system/string/)
* 클래스 [IFormatProvider](../../../system/iformatprovider/)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)