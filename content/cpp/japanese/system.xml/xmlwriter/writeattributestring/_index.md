---
title: WriteAttributeString()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、指定されたローカル名、名前空間URI、および値を持つ属性を書き込みます。
type: docs
weight: 131
url: /ja/system.xml/xmlwriter/writeattributestring/
---
## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&) メソッド

派生クラスでオーバーライドされた場合、指定されたローカル名、名前空間URI、および値を持つ属性を書き込みます。

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &ns, const String &value)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 属性のローカル名です。 |
| ns | const [String](../../../system/string/)\& | 属性に関連付ける名前空間URIです。 |
| value | const [String](../../../system/string/)\& | 属性の値です。 |

## XmlWriter::WriteAttributeString(const String\&, const String\&) メソッド

派生クラスでオーバーライドされた場合、指定されたローカル名と値を持つ属性を書き込みます。

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &value)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 属性のローカル名です。 |
| value | const [String](../../../system/string/)\& | 属性の値です。 |

## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&, const String\&) メソッド

派生クラスでオーバーライドされた場合、指定されたプレフィックス、ローカル名、名前空間URI、および値を持つ属性を書き込みます。

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &prefix, const String &localName, const String &ns, const String &value)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 属性の名前空間プレフィックスです。 |
| localName | const [String](../../../system/string/)\& | 属性のローカル名です。 |
| ns | const [String](../../../system/string/)\& | 属性の名前空間URIです。 |
| value | const [String](../../../system/string/)\& | 属性の値です。 |

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlWriter](../)
* 名前空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)