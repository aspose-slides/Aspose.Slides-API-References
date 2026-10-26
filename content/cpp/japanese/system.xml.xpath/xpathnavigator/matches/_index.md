---
title: Matches()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のノードが指定されたXPathExpressionに一致するかどうかを判断します。
type: docs
weight: 820
url: /ja/system.xml.xpath/xpathnavigator/matches/
---
## XPathNavigator::Matches(SharedPtr\<XPathExpression\>) メソッド

現在のノードが指定された[XPathExpression](../../xpathexpression/)に一致するかどうかを判断します。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(SharedPtr<XPathExpression> expr)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | [XPathExpression](../../xpathexpression/) オブジェクトで、コンパイル済みの[XPath](../../)式を含みます。 |

### 戻り値

現在のノードが[XPathExpression](../../xpathexpression/)に一致する場合は **true**、それ以外の場合は **false**。

## XPathNavigator::Matches(String) メソッド

現在のノードが指定された[XPath](../../)式に一致するかどうかを判断します。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(String xpath)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [XPath](../../) 式。 |

### 戻り値

現在のノードが指定された[XPath](../../)式に一致する場合は **true**、それ以外の場合は **false**。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XPathExpression](../../xpathexpression/)
* クラス [XPathNavigator](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)