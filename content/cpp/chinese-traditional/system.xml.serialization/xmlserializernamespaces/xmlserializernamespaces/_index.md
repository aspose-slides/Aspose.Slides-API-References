---
title: XmlSerializerNamespaces()
second_title: Aspose.Slides C++ API 參考文件
description: "初始化 Serialization::XmlSerializerNamespaces 類別的新執行個體。"
type: docs
weight: 53
url: /zh-hant/system.xml.serialization/xmlserializernamespaces/xmlserializernamespaces/
---
## XmlSerializerNamespaces::XmlSerializerNamespaces() 建構函式

初始化 [Serialization::XmlSerializerNamespaces](../) 類別的新執行個體。

```cpp
System::Xml::Serialization::XmlSerializerNamespaces::XmlSerializerNamespaces()
```

## XmlSerializerNamespaces::XmlSerializerNamespaces(const SharedPtr\<XmlSerializerNamespaces\>\&) 建構函式

初始化 [Serialization::XmlSerializerNamespaces](../) 類別的新執行個體，使用指定的 **[XmlSerializerNamespaces](../)** 實例，其中包含前置詞和命名空間配對的集合。

```cpp
System::Xml::Serialization::XmlSerializerNamespaces::XmlSerializerNamespaces(const SharedPtr<XmlSerializerNamespaces> &namespaces)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| namespaces | const [SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../)\>\& | 包含命名空間和前置詞配對的 [Serialization::XmlSerializerNamespaces](../) 實例。 |

## XmlSerializerNamespaces::XmlSerializerNamespaces(const ArrayPtr\<SharedPtr\<XmlQualifiedName\>\>\&) 建構函式

初始化 [Serialization::XmlSerializerNamespaces](../) 類別的新執行個體。

```cpp
System::Xml::Serialization::XmlSerializerNamespaces::XmlSerializerNamespaces(const ArrayPtr<SharedPtr<XmlQualifiedName>> &namespaces)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| namespaces | const [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\>\& | 一個 [XmlQualifiedName](../../../system.xml/xmlqualifiedname/) 物件的陣列。 |

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [XmlSerializerNamespaces](../)
* 類別 [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* 命名空間 [System::Xml::Serialization](../../)
* 函式庫 [Aspose.Slides](../../../)