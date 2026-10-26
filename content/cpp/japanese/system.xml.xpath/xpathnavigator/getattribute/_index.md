---
title: GetAttribute()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたローカル名と名前空間 URI を持つ属性の値を返します。
type: docs
weight: 482
url: /ja/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute(String, String) メソッド

指定されたローカル名および名前空間 URI を持つ属性の値を返します。

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 属性のローカル名。**localName** は大文字と小文字を区別します。 |
| namespaceURI | [String](../../../system/string/) | 属性の名前空間 URI。 |

### 戻り値

指定された属性の値を含む [String](../../../system/string/)。一致する属性が見つからない場合、または [XPathNavigator](../) が要素ノード上に位置していない場合は [String::Empty](../../../system/string/empty/)。

## 参照

* クラス [String](../../../system/string/)
* クラス [XPathNavigator](../)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)