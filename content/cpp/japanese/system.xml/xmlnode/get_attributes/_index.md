---
title: get_Attributes()
second_title: Aspose.Slides for C++ API リファレンス
description: このノードの属性を含む XmlAttributeCollection を返します。
type: docs
weight: 105
url: /ja/system.xml/xmlnode/get_attributes/
---
## XmlNode::get_Attributes() メソッド


このノードの属性を含む[XmlAttributeCollection](../../xmlattributecollection/)を返します。

```cpp
virtual SharedPtr<XmlAttributeCollection> System::Xml::XmlNode::get_Attributes() final
```


### 戻り値

ノードの属性を含む[XmlAttributeCollection](../../xmlattributecollection/)です。ノードが[XmlNodeType::Element](../../xmlnodetype/)型の場合、ノードの属性が返されます。それ以外の場合、このメソッドは**nullptr**を返します。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlAttributeCollection](../../xmlattributecollection/)
* クラス [XmlNode](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)