---
title: AddNamespace()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前空間をコレクションに追加します。
type: docs
weight: 66
url: /ja/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) メソッド

指定された名前空間をコレクションに追加します。

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 追加される名前空間に関連付けるプレフィックスです。[String::Empty](../../../system/string/empty/) を使用してデフォルト名前空間を追加します。[XmlNamespaceManager](../) が XML パス言語 ([XPath](../../../system.xml.xpath/)) 式で名前空間の解決に使用される場合、プレフィックスを指定する必要があります。[XPath](../../../system.xml.xpath/) 式にプレフィックスが含まれていない場合、名前空間の Uniform Resource Identifier (URI) は空の名前空間であるとみなされます。[XPath](../../../system.xml.xpath/) 式および [XmlNamespaceManager](../) の詳細については、XmlNode::SelectNodes(String) および XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>) メソッドを参照してください。 |
| uri | [String](../../../system/string/) | 追加する名前空間です。 |

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlNamespaceManager](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)