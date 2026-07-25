---
title: ReadAttributeValue()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、属性値を 1 つ以上の Text、EntityReference、または EndEntity ノードに解析します。
type: docs
weight: 677
url: /ja/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue() メソッド

派生クラスでオーバーライドされた場合、属性値を 1 つ以上の **[Text](../../../system.text/)**、**EntityReference**、または **EndEntity** ノードに解析します。

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```

### 戻り値

ノードが返される場合は **true** です。初回呼び出し時にリーダーが属性ノード上に位置していない場合、またはすべての属性値が読み取られた場合は **false** です。たとえば **misc=\"\"** のような空の属性は、値が [String::Empty](../../../system/string/empty/) の単一ノードを伴い **true** を返します。

## 参照

* クラス [XmlReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)