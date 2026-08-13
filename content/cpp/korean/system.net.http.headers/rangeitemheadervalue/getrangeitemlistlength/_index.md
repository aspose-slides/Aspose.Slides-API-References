---
title: GetRangeItemListLength()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 위치부터 전달된 문자열을 RangeItemHeaderValue 클래스 인스턴스의 컬렉션으로 변환합니다.
type: docs
weight: 79
url: /ko/system.net.http.headers/rangeitemheadervalue/getrangeitemlistlength/
---
## RangeItemHeaderValue::GetRangeItemListLength(String, int32_t, System::SharedPtr\<Collections::Generic::ICollection\<System::SharedPtr\<RangeItemHeaderValue\>\>\>) 메서드


지정된 위치부터 전달된 문자열을 RangeItemHeaderValue-class 인스턴스의 컬렉션으로 변환합니다.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength(String input, int32_t startIndex, System::SharedPtr<Collections::Generic::ICollection<System::SharedPtr<RangeItemHeaderValue>>> rangeCollection)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 구문 분석할 문자열. |
| startIndex | **int32_t** | 구문 분석을 위한 시작 위치. |
| rangeCollection | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\>\> | 구문 분석된 컬렉션이 할당될 인스턴스. |

### 반환 값

구문 분석된 하위 문자열의 길이, 그렇지 않으면 0.

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [ICollection](../../../system.collections.generic/icollection/)
* 클래스 [RangeItemHeaderValue](../)
* 네임스페이스 [System::Net::Http::Headers](../../)
* 라이브러리 [Aspose.Slides](../../../)