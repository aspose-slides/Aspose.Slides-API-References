---
title: ToString()
second_title: Aspose.Slides for C++ API 參考
description: C# Object.ToString() 方法的類比。允許將自訂物件轉換為字串。
type: docs
weight: 79
url: /zh-hant/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const 方法


Analog of C# [Object.ToString()](../../../system/object/tostring/) method. Enables converting custom objects to string.

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```


### 傳回值

[String](../../../system/string/)

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) 方法


Returns a string representation of the collection of the NameValueHeaderValue-class instances.

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | NameValueHeaderValue-class 實例的集合。 |
| separator | char16_t | 字串分隔符。 |
| leadingSeparator | **bool** | 指示是否在第一個集合項目之前必須加入字串分隔符的值。 |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | 用於指派字串表示形式的實例。 |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) 方法


Returns a string representation of the collection of the NameValueHeaderValue-class instances.

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | NameValueHeaderValue-class 實例的集合。 |
| separator | char16_t | 字串分隔符。 |
| leadingSeparator | **bool** | 指示是否在第一個集合項目之前必須加入字串分隔符的值。 |

### 傳回值

NameValueHeaderValue-class 實例集合的字串表示形式。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [NameValueHeaderValue](../)
* 類別 [ObjectCollection](../../objectcollection/)
* 類別 [StringBuilder](../../../system.text/stringbuilder/)
* 命名空間 [System::Net::Http::Headers](../../)
* 函式庫 [Aspose.Slides](../../../)