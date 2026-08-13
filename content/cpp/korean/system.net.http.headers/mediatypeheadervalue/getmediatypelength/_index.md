---
title: GetMediaTypeLength()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 지정된 인덱스에서 전달된 문자열을 MediaTypeHeaderValue 클래스의 인스턴스로 변환합니다.
type: docs
weight: 144
url: /ko/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) method

지정된 인덱스에서 전달된 문자열을 [MediaTypeHeaderValue](../) 클래스의 인스턴스로 변환합니다.

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 구문 분석할 문자열. |
| startIndex | **int32_t** | 구문 분석 시작 위치. |
| mediaTypeCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\> | [MediaTypeHeaderValue](../) 클래스의 인스턴스를 생성하는 데 사용되는 대리자. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | 구문 분석된 객체가 할당될 인스턴스. |

### 반환값

구문 분석된 부분 문자열의 길이를 반환하며, 그렇지 않으면 0을 반환합니다.

## 참고

* 타입정의 [HeaderFunc](../../headerfunc/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [MediaTypeHeaderValue](../)
* 네임스페이스 [System::Net::Http::Headers](../../)
* 라이브러리 [Aspose.Slides](../../../)