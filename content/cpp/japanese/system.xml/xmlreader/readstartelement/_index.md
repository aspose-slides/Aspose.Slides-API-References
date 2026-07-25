---
title: ReadStartElement()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のノードが要素であることを確認し、リーダーを次のノードに進めます。
type: docs
weight: 846
url: /ja/system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() メソッド


現在のノードが要素であることを確認し、リーダーを次のノードに進めます。

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```


## XmlReader::ReadStartElement(String) メソッド


現在のコンテンツノードが、指定された [XmlReader::get_Name](../get_name/) 値を持つ要素であることを確認し、リーダーを次のノードに進めます。

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要素の完全修飾名。 |

## XmlReader::ReadStartElement(String, String) メソッド


現在のコンテンツノードが、指定された [XmlReader::get_LocalName](../get_localname/) と [XmlReader::get_NamespaceURI](../get_namespaceuri/) の値を持つ要素であることを確認し、リーダーを次のノードに進めます。

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localname | [String](../../../system/string/) | 要素のローカル名。 |
| ns | [String](../../../system/string/) | 要素の名前空間 URI。 |

## 参照

* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)