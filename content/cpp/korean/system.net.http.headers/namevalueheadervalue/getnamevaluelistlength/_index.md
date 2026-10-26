---
title: GetNameValueListLength()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 인덱스부터 전달된 문자열을 NameValueHeaderValue 클래스 인스턴스 컬렉션으로 변환하고, 파싱된 서브스트링의 길이를 반환합니다.
type: docs
weight: 131
url: /ko/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) method

전달된 문자열을 지정된 인덱스부터 NameValueHeaderValue 클래스 인스턴스 컬렉션으로 변환하고, 파싱된 서브스트링의 길이를 반환합니다.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 분석할 문자열입니다. |
| startIndex | **int32_t** | 분석 시작 위치입니다. |
| delimiter | char16_t | 지정된 문자열에서 항목을 구분하는 데 사용되는 문자열입니다. |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | 파싱된 컬렉션이 할당되는 출력 매개변수입니다. |

### 반환값

파싱된 서브스트링의 길이입니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [ObjectCollection](../../objectcollection/)
* 클래스 [NameValueHeaderValue](../)
* 네임스페이스 [System::Net::Http::Headers](../../)
* 라이브러리 [Aspose.Slides](../../../)