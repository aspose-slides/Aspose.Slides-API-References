---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API リファレンス
description: XPathNavigator を、ローカル名と名前空間 URI が一致する属性へ移動します。
type: docs
weight: 495
url: /ja/system.xml.xpath/xpathnavigator/movetoattribute/
---
## XPathNavigator::MoveToAttribute(String, String) メソッド

[XPathNavigator](../) を、ローカル名と名前空間 URI が一致する属性へ移動します。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToAttribute(String localName, String namespaceURI)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 属性のローカル名。 |
| namespaceURI | [String](../../../system/string/) | 属性の名前空間 URI。空の名前空間の場合は **nullptr**。 |

### 戻り値

**true** は属性への移動が成功した場合の [XPathNavigator](../)；それ以外の場合は **false**。**false** の場合、[XPathNavigator](../) の位置は変更されません。

## 参照

* クラス [String](../../../system/string/)
* クラス [XPathNavigator](../)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)