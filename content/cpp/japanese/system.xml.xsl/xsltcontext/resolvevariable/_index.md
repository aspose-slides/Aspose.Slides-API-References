---
title: ResolveVariable()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、変数参照を解決し、変数を表す IXsltContextVariable を返します。
type: docs
weight: 14
url: /ja/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) メソッド

派生クラスでオーバーライドされた場合、変数参照を解決し、変数を表す [IXsltContextVariable](../../ixsltcontextvariable/) を返します。

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 変数が [XPath](../../../system.xml.xpath/) 式に現れる際のプレフィックスです。 |
| name | [String](../../../system/string/) | 変数の名前です。 |

### 戻り値

実行時に変数を表す [IXsltContextVariable](../../ixsltcontextvariable/) です。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IXsltContextVariable](../../ixsltcontextvariable/)
* クラス [String](../../../system/string/)
* クラス [XsltContext](../)
* 名前空間 [System::Xml::Xsl](../../)
* ライブラリ [Aspose.Slides](../../../)