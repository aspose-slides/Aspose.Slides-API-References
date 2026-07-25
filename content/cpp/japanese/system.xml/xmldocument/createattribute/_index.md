---
title: CreateAttribute()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前で XmlAttribute を作成します。
type: docs
weight: 274
url: /ja/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) メソッド

指定された名前で[XmlAttribute](../../xmlattribute/)を作成します。

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 属性の修飾名です。名前にコロンが含まれる場合、[XmlNode::get_Prefix](../../xmlnode/get_prefix/) の値は最初のコロンの前の部分を、[XmlDocument::get_LocalName](../get_localname/) の値はコロンの後の部分を表します。[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) は、プレフィックスが **xmlns** のような認識された組み込みプレフィックスでない限り空のままです。この場合、get_NamespaceURI の値は [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/) になります。 |

### 戻り値

新しい[XmlAttribute](../../xmlattribute/)です。

## XmlDocument::CreateAttribute(const String\&, const String\&) メソッド

指定された修飾名と[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)で[XmlAttribute](../../xmlattribute/)を作成します。

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | 属性の修飾名です。名前にコロンが含まれる場合、[XmlNode::get_Prefix](../../xmlnode/get_prefix/) の値はコロンの前の部分を、[XmlDocument::get_LocalName](../get_localname/) の値はコロンの後の部分を表します。 |
| namespaceURI | const [String](../../../system/string/)\& | 属性の namespaceURI です。修飾名に **xmlns** のプレフィックスが含まれる場合、このパラメーターは [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/) でなければなりません。 |

### 戻り値

新しい[XmlAttribute](../../xmlattribute/)です。

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) メソッド

指定された[XmlNode::get_Prefix](../../xmlnode/get_prefix/)、[XmlDocument::get_LocalName](../get_localname/)、[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)で[XmlAttribute](../../xmlattribute/)を作成します。

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 属性のプレフィックスです（存在する場合）。[String::Empty](../../../system/string/empty/) と **nullptr** は同等です。 |
| localName | const [String](../../../system/string/)\& | 属性のローカル名です。 |
| namespaceURI | const [String](../../../system/string/)\& | 属性の名前空間 URI です（存在する場合）。[String::Empty](../../../system/string/empty/) と **nullptr** は同等です。**prefix** が **xmlns** の場合、このパラメーターは [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;) でなければならず、そうでなければ例外がスローされます。 |

### 戻り値

新しい[XmlAttribute](../../xmlattribute/)です。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlAttribute](../../xmlattribute/)
* クラス [String](../../../system/string/)
* クラス [XmlDocument](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)