---
title: TryParse()
second_title: Aspose.Slides for C++ API 참조
description: 전달된 문자열을 ContentDispositionHeaderValue 클래스의 인스턴스로 변환하려고 시도합니다.
type: docs
weight: 287
url: /ko/system.net.http.headers/contentdispositionheadervalue/tryparse/
---
## ContentDispositionHeaderValue::TryParse(String, System::SharedPtr\<ContentDispositionHeaderValue\>\&) method


Tries to convert a passed string to an instance of the [ContentDispositionHeaderValue](../) class.

```cpp
static bool System::Net::Http::Headers::ContentDispositionHeaderValue::TryParse(String input, System::SharedPtr<ContentDispositionHeaderValue> &parsedValue)
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 구문 분석할 문자열. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ContentDispositionHeaderValue](../)\>\& | 구문 분석된 객체가 할당될 인스턴스. |

### 반환값

구문 분석이 성공적으로 완료되면 true, 그렇지 않으면 false.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ContentDispositionHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)