---
title: ToString()
second_title: Aspose.Slides for C++ API 레퍼런스
description: C# Object.ToString() 메서드와 유사합니다. 사용자 지정 개체를 문자열로 변환할 수 있습니다.
type: docs
weight: 79
url: /ko/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const 메서드


C# [Object.ToString()](../../../system/object/tostring/) 메서드와 유사합니다. 사용자 지정 개체를 문자열로 변환할 수 있습니다.

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```


### 반환 값

[String](../../../system/string/) representation as provided by final class.

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) 메서드


NameValueHeaderValue 클래스 인스턴스 컬렉션의 문자열 표현을 반환합니다.

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | NameValueHeaderValue 클래스 인스턴스의 컬렉션. |
| separator | char16_t | 문자열 구분자. |
| leadingSeparator | **bool** | 첫 번째 컬렉션 항목 앞에 문자열 구분자를 추가해야 하는지 여부를 나타내는 값. |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | 문자열 표현이 할당될 인스턴스. |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) 메서드


NameValueHeaderValue 클래스 인스턴스 컬렉션의 문자열 표현을 반환합니다.

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | NameValueHeaderValue 클래스 인스턴스의 컬렉션. |
| separator | char16_t | 문자열 구분자. |
| leadingSeparator | **bool** | 첫 번째 컬렉션 항목 앞에 문자열 구분자를 추가해야 하는지 여부를 나타내는 값. |

### 반환 값

NameValueHeaderValue 클래스 인스턴스 컬렉션의 문자열 표현.

## 또 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [NameValueHeaderValue](../)
* 클래스 [ObjectCollection](../../objectcollection/)
* 클래스 [StringBuilder](../../../system.text/stringbuilder/)
* 네임스페이스 [System::Net::Http::Headers](../../)
* 라이브러리 [Aspose.Slides](../../../)