---
title: GetViaLength()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 지정된 인덱스에서 전달된 문자열을 ViaHeaderValue 클래스의 인스턴스로 변환합니다.
type: docs
weight: 131
url: /ko/system.net.http.headers/viaheadervalue/getvialength/
---
## ViaHeaderValue::GetViaLength(String, int32_t, System::SharedPtr\<Object\>\&) 메서드

지정된 인덱스에서 전달된 문자열을 [ViaHeaderValue](../) 클래스의 인스턴스로 변환합니다.

```cpp
static int32_t System::Net::Http::Headers::ViaHeaderValue::GetViaLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 구문 분석할 문자열입니다. |
| startIndex | **int32_t** | 구문 분석을 위한 시작 위치입니다. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 구문 분석된 객체가 할당될 인스턴스입니다. |

### 반환 값

구문 분석된 하위 문자열의 길이를 반환하며, 그렇지 않으면 0을 반환합니다.

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [Object](../../../system/object/)
* 클래스 [ViaHeaderValue](../)
* 네임스페이스 [System::Net::Http::Headers](../../)
* 라이브러리 [Aspose.Slides](../../../)