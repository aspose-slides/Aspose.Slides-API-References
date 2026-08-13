---
title: TryParse()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 전달된 문자열을 ContentRangeHeaderValue 클래스의 인스턴스로 변환하려 시도합니다.
type: docs
weight: 157
url: /ko/system.net.http.headers/contentrangeheadervalue/tryparse/
---
## ContentRangeHeaderValue::TryParse(String, System::SharedPtr\<ContentRangeHeaderValue\>\&) 메서드

전달된 문자열을 [ContentRangeHeaderValue](../) 클래스의 인스턴스로 변환하려 시도합니다.

```cpp
static bool System::Net::Http::Headers::ContentRangeHeaderValue::TryParse(String input, System::SharedPtr<ContentRangeHeaderValue> &parsedValue)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 구문 분석할 문자열. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ContentRangeHeaderValue](../)\>\& | 구문 분석된 객체가 할당될 인스턴스. |

### 반환값

구문 분석이 성공적으로 완료되면 true, 그렇지 않으면 false.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ContentRangeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)