---
title: Transform()
second_title: Aspose.Slides for C++ API リファレンス
description: IXPathNavigable オブジェクトで指定された入力ドキュメントを使用して変換を実行し、結果を XmlWriter に出力します。
type: docs
weight: 40
url: /ja/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) メソッド

IXPathNavigable オブジェクトで指定された入力ドキュメントを使用して変換を実行し、結果を [XmlWriter](../../../system.xml/xmlwriter/) に出力します。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable インターフェイスを実装するオブジェクトです。[XmlNode](../../../system.xml/xmlnode/)（通常は [XmlDocument](../../../system.xml/xmldocument/)）または、変換対象データを含む XPathDocument のいずれかです。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) に出力します。スタイルシートに **xsl:output** 要素が含まれている場合、[XslCompiledTransform::get_OutputSettings](../get_outputsettings/) の値から返される [XmlWriterSettings](../../../system.xml/xmlwritersettings/) オブジェクトを使用して [XmlWriter](../../../system.xml/xmlwriter/) を作成する必要があります。これにより、[XmlWriter](../../../system.xml/xmlwriter/) が正しい出力設定を持つことが保証されます。 |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) メソッド

IXPathNavigable オブジェクトで指定された入力ドキュメントを使用して変換を実行し、結果を [XmlWriter](../../../system.xml/xmlwriter/) に出力します。[XsltArgumentList](../../xsltargumentlist/) は追加の実行時引数を提供します。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable インターフェイスを実装するオブジェクトです。[XmlNode](../../../system.xml/xmlnode/)（通常は [XmlDocument](../../../system.xml/xmldocument/)）または、変換対象データを含む XPathDocument のいずれかです。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 名前空間で修飾された引数を含む [XsltArgumentList](../../xsltargumentlist/) で、変換への入力として使用されます。この値は **nullptr** にできます。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) に出力します。スタイルシートに **xsl:output** 要素が含まれている場合、[XslCompiledTransform::get_OutputSettings](../get_outputsettings/) の値から返される [XmlWriterSettings](../../../system.xml/xmlwritersettings/) オブジェクトを使用して [XmlWriter](../../../system.xml/xmlwriter/) を作成する必要があります。これにより、[XmlWriter](../../../system.xml/xmlwriter/) が正しい出力設定を持つことが保証されます。 |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) メソッド

IXPathNavigable オブジェクトで指定された入力ドキュメントを使用して変換を実行し、結果を TextWriter に出力します。[XsltArgumentList](../../xsltargumentlist/) は追加の実行時引数を提供します。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable インターフェイスを実装するオブジェクトです。[XmlNode](../../../system.xml/xmlnode/)（通常は [XmlDocument](../../../system.xml/xmldocument/)）または、変換対象データを含む XPathDocument のいずれかです。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 名前空間で修飾された引数を含む [XsltArgumentList](../../xsltargumentlist/) で、変換への入力として使用されます。この値は **nullptr** にできます。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 出力先の TextWriter です。 |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) メソッド

IXPathNavigable オブジェクトで指定された入力ドキュメントを使用して変換を実行し、結果をストリームに出力します。[XsltArgumentList](../../xsltargumentlist/) は追加の実行時引数を提供します。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable インターフェイスを実装するオブジェクトです。[XmlNode](../../../system.xml/xmlnode/)（通常は [XmlDocument](../../../system.xml/xmldocument/)）または、変換対象データを含む XPathDocument のいずれかです。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 名前空間で修飾された引数を含む [XsltArgumentList](../../xsltargumentlist/) で、変換への入力として使用されます。この値は **nullptr** にできます。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 出力先のストリームです。 |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) メソッド

[XmlReader](../../../system.xml/xmlreader/) オブジェクトで指定された入力ドキュメントを使用して変換を実行し、結果を [XmlWriter](../../../system.xml/xmlwriter/) に出力します。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 入力ドキュメントを含む [XmlReader](../../../system.xml/xmlreader/) です。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 出力先の [XmlWriter](../../../system.xml/xmlwriter/) です。スタイルシートに **xsl:output** 要素が含まれている場合、[XslCompiledTransform::get_OutputSettings](../get_outputsettings/) の値から返される [XmlWriterSettings](../../../system.xml/xmlwritersettings/) オブジェクトを使用して [XmlWriter](../../../system.xml/xmlwriter/) を作成する必要があります。これにより、[XmlWriter](../../../system.xml/xmlwriter/) が正しい出力設定を持つことが保証されます。 |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) メソッド

[XmlReader](../../../system.xml/xmlreader/) オブジェクトで指定された入力ドキュメントを使用して変換を実行し、結果を [XmlWriter](../../../system.xml/xmlwriter/) に出力します。[XsltArgumentList](../../xsltargumentlist/) は追加の実行時引数を提供します。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 入力ドキュメントを含む [XmlReader](../../../system.xml/xmlreader/) です。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 名前空間で修飾された引数を含む [XsltArgumentList](../../xsltargumentlist/) で、変換への入力として使用されます。この値は **nullptr** にできます。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 出力先の [XmlWriter](../../../system.xml/xmlwriter/) です。スタイルシートに **xsl:output** 要素が含まれている場合、[XslCompiledTransform::get_OutputSettings](../get_outputsettings/) の値から返される [XmlWriterSettings](../../../system.xml/xmlwritersettings/) オブジェクトを使用して [XmlWriter](../../../system.xml/xmlwriter/) を作成する必要があります。これにより、[XmlWriter](../../../system.xml/xmlwriter/) が正しい出力設定を持つことが保証されます。 |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) メソッド

[XmlReader](../../../system.xml/xmlreader/) オブジェクトで指定された入力ドキュメントを使用して変換を実行し、結果を TextWriter に出力します。[XsltArgumentList](../../xsltargumentlist/) は追加の実行時引数を提供します。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 入力ドキュメントを含む [XmlReader](../../../system.xml/xmlreader/) です。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 名前空間で修飾された引数を含む [XsltArgumentList](../../xsltargumentlist/) で、変換への入力として使用されます。この値は **nullptr** にできます。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 出力先の TextWriter です。 |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) メソッド

[XmlReader](../../../system.xml/xmlreader/) オブジェクトで指定された入力ドキュメントを使用して変換を実行し、結果をストリームに出力します。[XsltArgumentList](../../xsltargumentlist/) は追加の実行時引数を提供します。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 入力ドキュメントを含む [XmlReader](../../../system.xml/xmlreader/) です。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 名前空間で修飾された引数を含む [XsltArgumentList](../../xsltargumentlist/) で、変換への入力として使用されます。この値は **nullptr** にできます。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 出力先のストリームです。 |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) メソッド

URI で指定された入力ドキュメントを使用して変換を実行し、結果を [XmlWriter](../../../system.xml/xmlwriter/) に出力します。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | 入力ドキュメントの URI です。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 出力先の [XmlWriter](../../../system.xml/xmlwriter/) です。スタイルシートに **xsl:output** 要素が含まれている場合、[XslCompiledTransform::get_OutputSettings](../get_outputsettings/) の値から返される [XmlWriterSettings](../../../system.xml/xmlwritersettings/) オブジェクトを使用して [XmlWriter](../../../system.xml/xmlwriter/) を作成する必要があります。これにより、[XmlWriter](../../../system.xml/xmlwriter/) が正しい出力設定を持つことが保証されます。 |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) メソッド

URI で指定された入力ドキュメントを使用して変換を実行し、結果を [XmlWriter](../../../system.xml/xmlwriter/) に出力します。[XsltArgumentList](../../xsltargumentlist/) は追加の実行時引数を提供します。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | 入力ドキュメントの URI です。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 名前空間で修飾された引数を含む [XsltArgumentList](../../xsltargumentlist/) で、変換への入力として使用されます。この値は **nullptr** にできます。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 出力先の [XmlWriter](../../../system.xml/xmlwriter/) です。スタイルシートに **xsl:output** 要素が含まれている場合、[XslCompiledTransform::get_OutputSettings](../get_outputsettings/) の値から返される [XmlWriterSettings](../../../system.xml/xmlwritersettings/) オブジェクトを使用して [XmlWriter](../../../system.xml/xmlwriter/) を作成する必要があります。これにより、[XmlWriter](../../../system.xml/xmlwriter/) が正しい出力設定を持つことが保証されます。 |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) メソッド

URI で指定された入力ドキュメントを使用して変換を実行し、結果を TextWriter に出力します。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | 入力ドキュメントの URI です。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 名前空間で修飾された引数を含む [XsltArgumentList](../../xsltargumentlist/) で、変換への入力として使用されます。この値は **nullptr** にできます。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 出力先の TextWriter です。 |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) メソッド

URI で指定された入力ドキュメントを使用して変換を実行し、結果をストリームに出力します。[XsltArgumentList](../../xsltargumentlist/) は追加の実行時引数を提供します。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | 入力ドキュメントの URI です。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 名前空間で修飾された引数を含む [XsltArgumentList](../../xsltargumentlist/) で、変換への入力として使用されます。この値は **nullptr** にできます。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 出力先のストリームです。 |

## XslCompiledTransform::Transform(const String\&, const String\&) メソッド

URI で指定された入力ドキュメントを使用して変換を実行し、結果をファイルに出力します。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | 入力ドキュメントの URI です。 |
| resultsFile | const [String](../../../system/string/)\& | 出力ファイルの URI です。 |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) メソッド

[XmlReader](../../../system.xml/xmlreader/) オブジェクトで指定された入力ドキュメントを使用して変換を実行し、結果を [XmlWriter](../../../system.xml/xmlwriter/) に出力します。[XsltArgumentList](../../xsltargumentlist/) は追加の実行時引数を提供し、[XmlResolver](../../../system.xml/xmlresolver/) は XSLT **document()** 関数を解決します。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 入力ドキュメントを含む [XmlReader](../../../system.xml/xmlreader/) です。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | 名前空間で修飾された引数を含む [XsltArgumentList](../../xsltargumentlist/) で、変換への入力として使用されます。この値は **nullptr** にできます。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 出力先の [XmlWriter](../../../system.xml/xmlwriter/) です。スタイルシートに **xsl:output** 要素が含まれている場合、[XslCompiledTransform::get_OutputSettings](../get_outputsettings/) の値から返される [XmlWriterSettings](../../../system.xml/xmlwritersettings/) オブジェクトを使用して [XmlWriter](../../../system.xml/xmlwriter/) を作成する必要があります。これにより、[XmlWriter](../../../system.xml/xmlwriter/) が正しい出力設定を持つことが保証されます。 |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** 関数を解決するために使用される [XmlResolver](../../../system.xml/xmlresolver/) です。この値が **nullptr** の場合、**document()** 関数は解決されません。 |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) メソッド

IXPathNavigable オブジェクトで指定された入力ドキュメントを使用して変換を実行し、結果を [XmlWriter](../../../system.xml/xmlwriter/) に出力します。[XsltArgumentList](../../xsltargumentlist/) は追加の実行時引数を提供し、[XmlResolver](../../../system.xml/xmlresolver/) は XSLT **document()** 関数を解決します。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable オブジェクトで指定された変換対象ドキュメントです。 |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) と同等の引数リストです。 |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | 出力先の [XmlWriter](../../../system.xml/xmlwriter/) です。スタイルシートに **xsl:output** 要素が含まれている場合、[XslCompiledTransform::get_OutputSettings](../get_outputsettings/) の値から返される [XmlWriterSettings](../../../system.xml/xmlwritersettings/) オブジェクトを使用して [XmlWriter](../../../system.xml/xmlwriter/) を作成する必要があります。これにより、[XmlWriter](../../../system.xml/xmlwriter/) が正しい出力設定を持つことが保証されます。 |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **document()** 関数を解決するために使用される [XmlResolver](../../../system.xml/xmlresolver/) です。この値が **nullptr** の場合、**document()** 関数は解決されません。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [String](../../../system/string/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)