---
title: XPathNodeType
second_title: C++ 用 Aspose.Slides API リファレンス
description: XPathNavigator クラスから返される XPath ノードタイプを定義します。
type: docs
weight: 157
url: /ja/system.xml.xpath/xpathnodetype/
---
## XPathNodeType 列挙型

Defines the [XPath](../) node types that can be returned from the [XPathNavigator](../xpathnavigator/) class.

```cpp
enum class XPathNodeType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Root | 0 | XML 文書またはノードツリーのルートノードです。 |
| Element | 1 | **<element>** のような要素です。 |
| Attribute | 2 | **id='123'** のような属性です。 |
| Namespace | 3 | **xmlns=\"namespace\"** のような名前空間です。 |
| Text | 4 | ノードのテキスト内容です。Document [Object](../../system/object/) Model (DOM) [Text](../../system.text/) および CDATA ノードタイプに相当します。少なくとも 1 文字が含まれます。 |
| SignificantWhitespace | 5 | 空白文字が含まれ、**xml:space** が **preserve** に設定されたノードです。 |
| Whitespace | 6 | 空白文字のみが含まれ、重要な空白がないノードです。空白文字は **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'** です。 |
| ProcessingInstruction | 7 | **<?pi test?>** のような処理指示です。この項目には XML 宣言は含まれず、[XPathNavigator](../xpathnavigator/) クラスからは見えません。 |
| Comment | 8 | **** のようなコメントです。 |
| All | 9 | 任意の XPathNodeType ノードタイプです。 |

## 参照

* 名前空間 [System::Xml::XPath](../)
* ライブラリ [Aspose.Slides](../../)