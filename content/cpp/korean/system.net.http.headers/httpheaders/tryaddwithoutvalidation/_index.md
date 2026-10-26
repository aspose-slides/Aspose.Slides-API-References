---
title: TryAddWithoutValidation()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 컬렉션에 새로운 이름-값 쌍을 추가하려 시도합니다.
type: docs
weight: 14
url: /ko/system.net.http.headers/httpheaders/tryaddwithoutvalidation/
---
## HttpHeaders::TryAddWithoutValidation(String, String) 메서드

새 이름-값 쌍을 현재 컬렉션에 추가하려 시도합니다.

```cpp
bool System::Net::Http::Headers::HttpHeaders::TryAddWithoutValidation(String name, String value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 헤더 이름입니다. |
| value | [String](../../../system/string/) | 헤더 값입니다. |

## HttpHeaders::TryAddWithoutValidation(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>) 메서드

이름-값 쌍 컬렉션을 현재 컬렉션에 추가합니다.

```cpp
bool System::Net::Http::Headers::HttpHeaders::TryAddWithoutValidation(String name, System::SharedPtr<Collections::Generic::IEnumerable<String>> values)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 헤더 이름입니다. |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\> | 헤더 값들입니다. |

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [HttpHeaders](../)
* 클래스 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 네임스페이스 [System::Net::Http::Headers](../../)
* 라이브러리 [Aspose.Slides](../../../)