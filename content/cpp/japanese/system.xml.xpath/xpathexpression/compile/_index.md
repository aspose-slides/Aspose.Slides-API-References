---
title: Compile()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたXPath式をコンパイルし、そのXPath式を表すXPathExpressionオブジェクトを返します。
type: docs
weight: 66
url: /ja/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) メソッド

指定された[XPath](../../)式をコンパイルし、[XPath](../../)式を表す[XPathExpression](../)オブジェクトを返します。

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../)式。 |

### 戻り値

[XPathExpression](../)オブジェクト。

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) メソッド

指定された[XPath](../../)式をコンパイルし、名前空間解決に使用する[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)オブジェクトを指定し、[XPath](../../)式を表す[XPathExpression](../)オブジェクトを返します。

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../)式。 |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | 名前空間解決のために[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)インターフェイスを実装したオブジェクト。 |

### 戻り値

[XPathExpression](../)オブジェクト。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XPathExpression](../)
* クラス [String](../../../system/string/)
* クラス [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)