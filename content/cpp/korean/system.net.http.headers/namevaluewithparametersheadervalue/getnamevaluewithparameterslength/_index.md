---
title: GetNameValueWithParametersLength()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 인덱스부터 전달된 문자열을 NameValueWithParametersHeaderValue 클래스의 인스턴스로 변환합니다.
type: docs
weight: 92
url: /ko/system.net.http.headers/namevaluewithparametersheadervalue/getnamevaluewithparameterslength/
---
## NameValueWithParametersHeaderValue::GetNameValueWithParametersLength(String, int32_t, System::SharedPtr\<Object\>\&) method


지정된 인덱스부터 전달된 문자열을 [NameValueWithParametersHeaderValue](../) 클래스의 인스턴스로 변환합니다.

```cpp
static int32_t System::Net::Http::Headers::NameValueWithParametersHeaderValue::GetNameValueWithParametersLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 구문 분석할 문자열. |
| startIndex | **int32_t** | 구문 분석 시작 위치. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 구문 분석된 객체가 할당될 인스턴스. |

### 반환값

구문 분석된 하위 문자열의 길이를 반환하며, 그렇지 않으면 0을 반환합니다.

## 또한 보기

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [Object](../../../system/object/)
* 클래스 [NameValueWithParametersHeaderValue](../)
* 네임스페이스 [System::Net::Http::Headers](../../)
* 라이브러리 [Aspose.Slides](../../../)