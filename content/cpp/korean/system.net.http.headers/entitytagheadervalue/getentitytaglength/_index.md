---
title: GetEntityTagLength()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 인덱스에서 전달된 문자열을 EntityTagHeaderValue 클래스의 인스턴스로 변환합니다.
type: docs
weight: 118
url: /ko/system.net.http.headers/entitytagheadervalue/getentitytaglength/
---
## EntityTagHeaderValue::GetEntityTagLength(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) 메서드

지정된 인덱스에서 전달된 문자열을 [EntityTagHeaderValue](../) 클래스의 인스턴스로 변환합니다.

```cpp
static int32_t System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength(String input, int32_t startIndex, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 구문 분석할 문자열. |
| startIndex | **int32_t** | 구문 분석을 위한 시작 위치. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | 구문 분석된 객체가 할당될 인스턴스. |

### 반환 값

구문 분석된 부분 문자열의 길이이며, 그렇지 않을 경우 0을 반환합니다.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [EntityTagHeaderValue](../)
* 네임스페이스 [System::Net::Http::Headers](../../)
* 라이브러리 [Aspose.Slides](../../../)