---
title: GetTransferCodingLength()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 인덱스부터 전달된 문자열을 TransferCodingHeaderValue 클래스의 인스턴스로 변환합니다.
type: docs
weight: 105
url: /ko/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) 메서드

지정된 인덱스부터 전달된 문자열을 [TransferCodingHeaderValue](../) 클래스의 인스턴스로 변환합니다.

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 구문 분석할 문자열. |
| startIndex | **int32_t** | 구문 분석을 위한 시작 위치. |
| parsedValue | const [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\>\& | 구문 분석된 객체가 할당될 인스턴스. |
| transferCodingCreator | [System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\& | [TransferCodingHeaderValue](../) 클래스의 인스턴스를 만드는 데 사용되는 대리자. |

### 반환값

구문 분석된 하위 문자열의 길이를 반환하며, 그렇지 않으면 0을 반환합니다.

## 참고

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [TransferCodingHeaderValue](../)
* 네임스페이스 [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)