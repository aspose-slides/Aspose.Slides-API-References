---
title: ResolveFunction()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、関数参照を解決し、関数を表す IXsltContextFunction を返します。IXsltContextFunction は実行時に関数の戻り値を取得するために使用されます。
type: docs
weight: 27
url: /ja/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) メソッド

派生クラスでオーバーライドされた場合、関数参照を解決し、関数を表す [IXsltContextFunction](../../ixsltcontextfunction/) を返します。[IXsltContextFunction](../../ixsltcontextfunction/) は実行時に関数の戻り値を取得するために使用されます。

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | [XPath](../../../system.xml.xpath/) 式に現れる関数のプレフィックス。 |
| name | [String](../../../system/string/) | 関数の名前。 |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | 解決される関数の引数型の配列です。同名のメソッド（例えばオーバーロードされたメソッド）間で選択できるようにします。 |

### 戻り値

関数を表す [IXsltContextFunction](../../ixsltcontextfunction/)。

## 参照

* 列挙型 [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [IXsltContextFunction](../../ixsltcontextfunction/)
* クラス [String](../../../system/string/)
* クラス [XsltContext](../)
* 名前空間 [System::Xml::Xsl](../../)
* ライブラリ [Aspose.Slides](../../../)