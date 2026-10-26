---
title: Evaluate()
second_title: Aspose.Slides for C++ API リファレンス
description: 実行時に変数を評価し、変数の値を表すオブジェクトを返します。
type: docs
weight: 40
url: /ja/system.xml.xsl/ixsltcontextvariable/evaluate/
---
## IXsltContextVariable::Evaluate(SharedPtr\<XsltContext\>) メソッド

実行時に変数を評価し、変数の値を表すオブジェクトを返します。

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextVariable::Evaluate(SharedPtr<XsltContext> xsltContext)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | [XsltContext](../../xsltcontext/) は変数の実行コンテキストを表します。 |

### 戻り値

[Object](../../../system/object/) は変数の値を表します。可能な戻り型には number、string、[Boolean](../../../system/boolean/)、document fragment、または node set が含まれます。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [XsltContext](../../xsltcontext/)
* クラス [IXsltContextVariable](../)
* 名前空間 [System::Xml::Xsl](../../)
* ライブラリ [Aspose.Slides](../../../)