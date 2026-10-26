---
title: XmlValidatingReader()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された XmlReader から返されるコンテンツを検証する XmlValidatingReader クラスの新しいインスタンスを初期化します。
type: docs
weight: 430
url: /ja/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) constructor

[XmlValidatingReader](../) クラスの新しいインスタンスを初期化し、指定された [XmlReader](../../xmlreader/) から返されるコンテンツを検証します。

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | The [XmlReader](../../xmlreader/) to read from while validating. The current implementation supports only [XmlTextReader](../../xmltextreader/). |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

[XmlValidatingReader](../) クラスの新しいインスタンスを、指定された値で初期化します。

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | The string containing the XML fragment to parse. |
| fragType | [XmlNodeType](../../xmlnodetype/) | The XmlNodeType of the XML fragment. This also determines what the fragment string can contain (see table below). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | The [XmlParserContext](../../xmlparsercontext/) in which the XML fragment is to be parsed. This includes the [NameTable](../../nametable/) to use, encoding, namespace scope, current **xml:lang**, and **xml:space** scope. |

## 備考

以下の表は **fragType** の有効な値と、リーダーが各ノードタイプをどのように解析するかを示しています。

| XmlNodeType | Fragment May Contain |
| --- | --- |
| Element| 有効な要素コンテンツ全般（例: 要素、コメント、処理命令、CDATA、テキスト、エンティティ参照の任意の組み合わせ）。 |
| [Attribute](../../../system/attribute/)| 属性の値（引用符内の部分）。 |
| Document| XML ドキュメント全体の内容。ドキュメントレベルの規則が適用されます。 |

## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

[XmlValidatingReader](../) クラスの新しいインスタンスを、指定された値で初期化します。

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | The stream containing the XML fragment to parse. |
| fragType | [XmlNodeType](../../xmlnodetype/) | The XmlNodeType of the XML fragment. This determines what the fragment can contain (see table below). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | The [XmlParserContext](../../xmlparsercontext/) in which the XML fragment is to be parsed. This includes the [XmlNameTable](../../xmlnametable/) to use, encoding, namespace scope, current **xml:lang**, and **xml:space** scope. |

## 備考

以下の表は **fragType** の有効な値と、リーダーが各ノードタイプをどのように解析するかを示しています。

| XmlNodeType | Fragment May Contain |
| --- | --- |
| Element| 有効な要素コンテンツ全般（例: 要素、コメント、処理命令、CDATA、テキスト、エンティティ参照の任意の組み合わせ）。 |
| [Attribute](../../../system/attribute/)| 属性の値（引用符内の部分）。 |
| Document| XML ドキュメント全体の内容。ドキュメントレベルの規則が適用されます。 |

## 参照

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlValidatingReader](../)
* Class [String](../../../system/string/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)