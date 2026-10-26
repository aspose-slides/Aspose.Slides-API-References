---
title: GetHashCode()
second_title: Aspose.Slides for C++ API 참조
description: C# Object.GetHashCode() 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다.
type: docs
weight: 53
url: /ko/system.net.http.headers/namevalueheadervalue/gethashcode/
---
## NameValueHeaderValue::GetHashCode() const 메서드


C# [Object.GetHashCode()](../../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다.

```cpp
int32_t System::Net::Http::Headers::NameValueHeaderValue::GetHashCode() const override
```


### 반환 값

해시 코드 값은 해당 클래스에 의해 계산됩니다.

## NameValueHeaderValue::GetHashCode(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) 메서드


컬렉션 항목 전체의 해시 코드를 반환합니다.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetHashCode(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | NameValueHeaderValue-클래스 인스턴스의 컬렉션입니다. |

### 반환 값

컬렉션 항목 전체의 해시 코드입니다.

## 또 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [NameValueHeaderValue](../)
* 클래스 [ObjectCollection](../../objectcollection/)
* 네임스페이스 [System::Net::Http::Headers](../../)
* 라이브러리 [Aspose.Slides](../../../)