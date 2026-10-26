---
title: Invoke()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたコンテキストで、指定された引数を使用して関数を呼び出すメソッドを提供します。
type: docs
weight: 53
url: /ja/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) メソッド

指定されたコンテキストで、指定された引数を使用して関数を呼び出すメソッドを提供します。

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | 関数呼び出しのための XSLT コンテキスト。 |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | 関数呼び出しの引数です。各引数は配列の要素です。 |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | 関数呼び出しのコンテキストノード。 |

### 戻り値

関数の戻り値を表す [Object](../../../system/object/)。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [Object](../../../system/object/)
* クラス [XsltContext](../../xsltcontext/)
* クラス [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* クラス [IXsltContextFunction](../)
* 名前空間 [System::Xml::Xsl](../../)
* ライブラリ [Aspose.Slides](../../../)