---
title: GetAuthenticationLength()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자열을 파싱하고 문자열 표현의 마지막 인덱스를 반환합니다.
type: docs
weight: 118
url: /ko/system.net.http.headers/authenticationheadervalue/getauthenticationlength/
---
## AuthenticationHeaderValue::GetAuthenticationLength(String, int32_t, System::SharedPtr\<Object\>\&) 메서드

지정된 문자열을 파싱하고 문자열 표현의 마지막 인덱스를 반환합니다.

```cpp
static int32_t System::Net::Http::Headers::AuthenticationHeaderValue::GetAuthenticationLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 파싱해야 하는 문자열입니다. |
| startIndex | **int32_t** | 파싱을 위한 시작 위치입니다. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 파싱된 값이 할당될 출력 매개변수입니다. |

### 반환 값

파싱된 하위 문자열의 길이, 그렇지 않으면 0.

## 또 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [Object](../../../system/object/)
* 클래스 [AuthenticationHeaderValue](../)
* 네임스페이스 [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)