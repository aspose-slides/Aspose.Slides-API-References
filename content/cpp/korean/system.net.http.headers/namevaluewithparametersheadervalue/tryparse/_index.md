---
title: TryParse()
second_title: Aspose.Slides for C++ API 참조
description: 전달된 문자열을 NameValueWithParametersHeaderValue 클래스의 인스턴스로 변환을 시도합니다.
type: docs
weight: 79
url: /ko/system.net.http.headers/namevaluewithparametersheadervalue/tryparse/
---
## NameValueWithParametersHeaderValue::TryParse(String, System::SharedPtr\<NameValueWithParametersHeaderValue\>\&) 메서드

전달된 문자열을 [NameValueWithParametersHeaderValue](../) 클래스의 인스턴스로 변환을 시도합니다.

```cpp
static bool System::Net::Http::Headers::NameValueWithParametersHeaderValue::TryParse(String input, System::SharedPtr<NameValueWithParametersHeaderValue> &parsedValue)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 구문 분석할 문자열. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueWithParametersHeaderValue](../)\>\& | 구문 분석된 객체가 할당될 인스턴스. |

### 반환 값

구문 분석이 성공적으로 완료되면 true, 그렇지 않으면 false.

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [NameValueWithParametersHeaderValue](../)
* 네임스페이스 [System::Net::Http::Headers](../../)
* 라이브러리 [Aspose.Slides](../../../)