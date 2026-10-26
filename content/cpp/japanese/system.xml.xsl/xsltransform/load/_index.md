---
title: Load()
second_title: Aspose.Slides for C++ API リファレンス
description: XmlReader に含まれる XSLT スタイルシートをロードします。
type: docs
weight: 27
url: /ja/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) メソッド

[XmlReader](../../../system.xml/xmlreader/) に含まれる XSLT スタイルシートをロードします。

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | XSLT スタイルシートを含む [XmlReader](../../../system.xml/xmlreader/) オブジェクトです。 |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) メソッド

[XmlReader](../../../system.xml/xmlreader/) に含まれる XSLT スタイルシートをロードします。

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | XSLT スタイルシートを含む [XmlReader](../../../system.xml/xmlreader/) オブジェクトです。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) は **xsl:import** および **xsl:include** 要素で参照されるすべてのスタイルシートをロードするために使用されます。これが **nullptr** の場合、外部リソースは解決されません。[XmlResolver](../../../system.xml/xmlresolver/) はこのメソッドが完了した後にキャッシュされません。 |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) メソッド

IXPathNavigable に含まれる XSLT スタイルシートをロードします。

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable インターフェイスを実装するオブジェクトです。[XmlNode](../../../system.xml/xmlnode/)（通常は [XmlDocument](../../../system.xml/xmldocument/)）または、XSLT スタイルシートを含む XPathDocument のいずれかです。 |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) メソッド

IXPathNavigable に含まれる XSLT スタイルシートをロードします。

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable インターフェイスを実装するオブジェクトです。[XmlNode](../../../system.xml/xmlnode/)（通常は [XmlDocument](../../../system.xml/xmldocument/)）または、XSLT スタイルシートを含む XPathDocument のいずれかです。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) は **xsl:import** および **xsl:include** 要素で参照されるすべてのスタイルシートをロードするために使用されます。これが **nullptr** の場合、外部リソースは解決されません。[XmlResolver](../../../system.xml/xmlresolver/) はこのメソッドが完了した後にキャッシュされません。 |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) メソッド

XPathNavigator に含まれる XSLT スタイルシートをロードします。

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XSLT スタイルシートを含む XPathNavigator オブジェクトです。 |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) メソッド

XPathNavigator に含まれる XSLT スタイルシートをロードします。

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XSLT スタイルシートを含む XPathNavigator オブジェクトです。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) は **xsl:import** および **xsl:include** 要素で参照されるすべてのスタイルシートをロードするために使用されます。これが **nullptr** の場合、外部リソースは解決されません。[XmlResolver](../../../system.xml/xmlresolver/) はこのメソッドが完了した後にキャッシュされません。 |

## XslTransform::Load(const String\&) メソッド

URL で指定された XSLT スタイルシートをロードします。

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | ロードする XSLT スタイルシートを指定する URL です。 |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) メソッド

URL で指定された XSLT スタイルシートをロードします。

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | ロードする XSLT スタイルシートを指定する URL です。 |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) はスタイルシートと **xsl:import** および **xsl:include** 要素で参照されるすべてのスタイルシートをロードするために使用されます。これが **nullptr** の場合、ユーザー資格情報なしのデフォルト [XmlUrlResolver](../../../system.xml/xmlurlresolver/) がスタイルシートを開くために使用されます。デフォルト [XmlUrlResolver](../../../system.xml/xmlurlresolver/) はスタイルシート内の外部リソースを解決するためには使用されず、したがって **xsl:import** および **xsl:include** 要素は解決されません。[XmlResolver](../../../system.xml/xmlresolver/) はこのメソッドが完了した後にキャッシュされません。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlReader](../../../system.xml/xmlreader/)
* クラス [XslTransform](../)
* クラス [XmlResolver](../../../system.xml/xmlresolver/)
* クラス [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* クラス [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* クラス [String](../../../system/string/)
* 名前空間 [System::Xml::Xsl](../../)
* ライブラリ [Aspose.Slides](../../../)