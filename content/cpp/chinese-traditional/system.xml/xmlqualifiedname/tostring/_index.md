---
title: ToString()
second_title: Aspose.Slides for C++ API 參考
description: 傳回 XmlQualifiedName 的字串值。
type: docs
weight: 79
url: /zh-hant/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const 方法

傳回 [XmlQualifiedName](../) 的字串值。

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```

### 回傳值

以 **namespace:localname** 格式的 [XmlQualifiedName](../) 字串值。如果物件未定義命名空間，此方法僅傳回本機名稱。

## XmlQualifiedName::ToString(const String\&, const String\&) 方法

傳回 [XmlQualifiedName](../) 的字串值。

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 物件的名稱。 |
| ns | const [String](../../../system/string/)\& | 物件的命名空間。 |

### 回傳值

以 **namespace:localname** 格式的 [XmlQualifiedName](../) 字串值。如果物件未定義命名空間，此方法僅傳回本機名稱。

## 參考

* 類別 [String](../../../system/string/)
* 類別 [XmlQualifiedName](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)