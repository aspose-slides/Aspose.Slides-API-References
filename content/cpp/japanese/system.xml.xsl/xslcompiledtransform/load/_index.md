---
title: Load()
second_title: Aspose.Slides for C++ API リファレンス
description: XmlReader に含まれるスタイルシートをコンパイルします。
type: docs
weight: 27
url: /ja/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) メソッド


[XmlReader](../../../system.xml/xmlreader/) に含まれるスタイルシートをコンパイルします。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | スタイルシートを含む [XmlReader](../../../system.xml/xmlreader/)。 |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) メソッド


[XmlReader](../../../system.xml/xmlreader/) に含まれる XSLT スタイルシートをコンパイルします。[XmlResolver](../../../system.xml/xmlresolver/) は XSLT **import** または **include** 要素を解決し、XSLT 設定はスタイルシートの許可を決定します。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | スタイルシートを含む [XmlReader](../../../system.xml/xmlreader/)。 |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | [XsltSettings](../../xsltsettings/) をスタイルシートに適用します。これが **nullptr** の場合、[XsltSettings::get_Default](../../xsltsettings/get_default/) 設定が適用されます。 |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) は XSLT **import** と **include** 要素で参照されるスタイルシートを解決するために使用されます。これが **nullptr** の場合、外部リソースは解決されません。 |

## XslCompiledTransform::Load(const String\&) メソッド


指定された URI にあるスタイルシートを読み込み、コンパイルします。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | スタイルシートの URI。 |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) メソッド


URI で指定された XSLT スタイルシートを読み込み、コンパイルします。[XmlResolver](../../../system.xml/xmlresolver/) は XSLT **import** または **include** 要素を解決し、XSLT 設定はスタイルシートの許可を決定します。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | スタイルシートの URI。 |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | [XsltSettings](../../xsltsettings/) をスタイルシートに適用します。これが **nullptr** の場合、[XsltSettings::get_Default](../../xsltsettings/get_default/) 設定が適用されます。 |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) はスタイルシートの URI と XSLT **import** と **include** 要素で参照されるすべてのスタイルシートを解決するために使用されます。 |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) メソッド


IXPathNavigable オブジェクトに含まれるスタイルシートをコンパイルします。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable インターフェイスを実装したオブジェクトです。[XmlNode](../../../system.xml/xmlnode/)（通常は [XmlDocument](../../../system.xml/xmldocument/)）またはスタイルシートを含む XPathDocument のいずれかです。 |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) メソッド


IXPathNavigable に含まれる XSLT スタイルシートをコンパイルします。[XmlResolver](../../../system.xml/xmlresolver/) は XSLT **import** または **include** 要素を解決し、XSLT 設定はスタイルシートの許可を決定します。

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable インターフェイスを実装したオブジェクトです。[XmlNode](../../../system.xml/xmlnode/)（通常は [XmlDocument](../../../system.xml/xmldocument/)）またはスタイルシートを含む XPathDocument のいずれかです。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | [XsltSettings](../../xsltsettings/) をスタイルシートに適用します。これが **nullptr** の場合、[XsltSettings::get_Default](../../xsltsettings/get_default/) 設定が適用されます。 |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | [XmlResolver](../../../system.xml/xmlresolver/) は XSLT **import** と **include** 要素で参照されるスタイルシートを解決するために使用されます。これが **nullptr** の場合、外部リソースは解決されません。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlReader](../../../system.xml/xmlreader/)
* クラス [XslCompiledTransform](../)
* クラス [XsltSettings](../../xsltsettings/)
* クラス [XmlResolver](../../../system.xml/xmlresolver/)
* クラス [String](../../../system/string/)
* クラス [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* 名前空間 [System::Xml::Xsl](../../)
* ライブラリ [Aspose.Slides](../../../)