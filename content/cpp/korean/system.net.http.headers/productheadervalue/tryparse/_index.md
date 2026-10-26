---
title: TryParse()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 전달된 문자열을 ProductHeaderValue 클래스의 인스턴스로 변환하려 시도합니다.
type: docs
weight: 92
url: /ko/system.net.http.headers/productheadervalue/tryparse/
---
## ProductHeaderValue::TryParse(String, System::SharedPtr\<ProductHeaderValue\>\&) 메서드


전달된 문자열을 [ProductHeaderValue](../) 클래스의 인스턴스로 변환하려 시도합니다.

```cpp
static bool System::Net::Http::Headers::ProductHeaderValue::TryParse(String input, System::SharedPtr<ProductHeaderValue> &parsedValue)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 구문 분석할 문자열입니다. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductHeaderValue](../)\>\& | 구문 분석된 객체가 할당될 인스턴스입니다. |

### 반환 값

구문 분석이 성공적으로 완료되면 true, 그렇지 않으면 false.

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [ProductHeaderValue](../)
* 네임스페이스 [System::Net::Http::Headers](../../)
* 라이브러리 [Aspose.Slides](../../../)