---
title: TryParse()
second_title: Aspose.Slides for C++ API 참조
description: 전달된 문자열을 RetryConditionHeaderValue 클래스의 인스턴스로 변환을 시도합니다.
type: docs
weight: 92
url: /ko/system.net.http.headers/retryconditionheadervalue/tryparse/
---
## RetryConditionHeaderValue::TryParse(String, System::SharedPtr\<RetryConditionHeaderValue\>\&) 메서드

전달된 문자열을 [RetryConditionHeaderValue](../) 클래스의 인스턴스로 변환을 시도합니다.

```cpp
static bool System::Net::Http::Headers::RetryConditionHeaderValue::TryParse(String input, System::SharedPtr<RetryConditionHeaderValue> &parsedValue)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 구문 분석할 문자열. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[RetryConditionHeaderValue](../)\>\& | 구문 분석된 객체가 할당될 인스턴스. |

### 반환 값

구문 분석이 성공적으로 완료되면 true, 그렇지 않으면 false.

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [RetryConditionHeaderValue](../)
* 네임스페이스 [System::Net::Http::Headers](../../)
* 라이브러리 [Aspose.Slides](../../../)