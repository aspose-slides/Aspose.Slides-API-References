---
title: TryParse()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 전달된 문자열을 CacheControlHeaderValue 클래스의 인스턴스로 변환하려 시도합니다.
type: docs
weight: 443
url: /ko/system.net.http.headers/cachecontrolheadervalue/tryparse/
---
## CacheControlHeaderValue::TryParse(String, System::SharedPtr\<CacheControlHeaderValue\>\&) method

전달된 문자열을 [CacheControlHeaderValue](../) 클래스의 인스턴스로 변환하려 시도합니다.

```cpp
static bool System::Net::Http::Headers::CacheControlHeaderValue::TryParse(String input, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 구문 분석할 문자열. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | 구문 분석된 객체가 할당될 인스턴스. |

### 반환값

구문 분석이 성공하면 true, 그렇지 않으면 false.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [CacheControlHeaderValue](../)
* 네임스페이스 [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)