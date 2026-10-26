---
title: ToString()
second_title: Aspose.Slides for C++ API 参考
description: C# Object.ToString() 方法的等价实现。支持将自定义对象转换为字符串。
type: docs
weight: 79
url: /zh/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const 方法

C# [Object.ToString()](../../../system/object/tostring/) 方法的类似实现。启用将自定义对象转换为字符串。

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```

### 返回值

[String](../../../system/string/) 表示，由最终类提供。

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) 方法

返回 NameValueHeaderValue 类实例集合的字符串表示。

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | NameValueHeaderValue 类实例的集合。 |
| separator | char16_t | 字符串分隔符。 |
| leadingSeparator | **bool** | 指示是否必须在第一个集合项之前添加字符串分隔符的值。 |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | 将分配字符串表示的实例。 |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) 方法

返回 NameValueHeaderValue 类实例集合的字符串表示。

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | NameValueHeaderValue 类实例的集合。 |
| separator | char16_t | 字符串分隔符。 |
| leadingSeparator | **bool** | 指示是否必须在第一个集合项之前添加字符串分隔符的值。 |

### 返回值

NameValueHeaderValue 类实例集合的字符串表示。

## 另请参见

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [NameValueHeaderValue](../)
* 类 [ObjectCollection](../../objectcollection/)
* 类 [StringBuilder](../../../system.text/stringbuilder/)
* 命名空间 [System::Net::Http::Headers](../../)
* 库 [Aspose.Slides](../../../)