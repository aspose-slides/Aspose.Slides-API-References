---
title: CompareDocument()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、XSLT プロセッサ（すなわち XslTransform クラス）によってドキュメントが読み込まれた順序に基づき、2つのドキュメントの基本 Uniform Resource Identifiers（URIs）を比較します。
type: docs
weight: 53
url: /ja/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) メソッド

派生クラスでオーバーライドされた場合、XSLTプロセッサ（つまり、[XslTransform](../../xsltransform/) クラス）によってドキュメントが読み込まれた順序に基づいて、2つのドキュメントの基本 Uniform Resource Identifiers（URI）を比較します。

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | 比較対象となる最初のドキュメントの基本 URI。 |
| nextbaseUri | [String](../../../system/string/) | 比較対象となる2番目のドキュメントの基本 URI。 |

### 戻り値

2つの基本 URI の相対的な順序を示す整数値です: **baseUri** が **nextbaseUri** の前にある場合は -1、2つの基本 URI が同一の場合は 0、**baseUri** が **nextbaseUri** の後にある場合は 1。

## 参照

* クラス [String](../../../system/string/)
* クラス [XsltContext](../)
* 名前空間 [System::Xml::Xsl](../../)
* ライブラリ [Aspose.Slides](../../../)