---
title: XmlSerializerNamespaces()
second_title: Aspose.Slides for C++ API リファレンス
description: "Serialization::XmlSerializerNamespaces クラスの新しいインスタンスを初期化します。"
type: docs
weight: 53
url: /ja/system.xml.serialization/xmlserializernamespaces/xmlserializernamespaces/
---
## XmlSerializerNamespaces::XmlSerializerNamespaces() コンストラクタ

新しい [Serialization::XmlSerializerNamespaces](../) クラスのインスタンスを初期化します。

```cpp
System::Xml::Serialization::XmlSerializerNamespaces::XmlSerializerNamespaces()
```

## XmlSerializerNamespaces::XmlSerializerNamespaces(const SharedPtr\<XmlSerializerNamespaces\>\&) コンストラクタ

指定された prefix と namespace のペアのコレクションを含む **[XmlSerializerNamespaces](../)** のインスタンスを使用して、新しい [Serialization::XmlSerializerNamespaces](../) クラスのインスタンスを初期化します。

```cpp
System::Xml::Serialization::XmlSerializerNamespaces::XmlSerializerNamespaces(const SharedPtr<XmlSerializerNamespaces> &namespaces)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| namespaces | const [SharedPtr](../../../system/sharedptr/)\<[XmlSerializerNamespaces](../)\>\& | namespace と prefix のペアを含む [Serialization::XmlSerializerNamespaces](../) のインスタンスです。 |

## XmlSerializerNamespaces::XmlSerializerNamespaces(const ArrayPtr\<SharedPtr\<XmlQualifiedName\>\>\&) コンストラクタ

新しい [Serialization::XmlSerializerNamespaces](../) クラスのインスタンスを初期化します。

```cpp
System::Xml::Serialization::XmlSerializerNamespaces::XmlSerializerNamespaces(const ArrayPtr<SharedPtr<XmlQualifiedName>> &namespaces)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| namespaces | const [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\>\& | [XmlQualifiedName](../../../system.xml/xmlqualifiedname/) オブジェクトの配列です。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [XmlSerializerNamespaces](../)
* クラス [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* 名前空間 [System::Xml::Serialization](../../)
* Library [Aspose.Slides](../../../)