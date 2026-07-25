---
title: ReadAttributeValue()
second_title: Aspose.Slides for C++ API リファレンス
description: 属性値を 1 つ以上の Text、EntityReference、または EndEntity ノードに解析します。
type: docs
weight: 430
url: /ja/system.xml/xmlnodereader/readattributevalue/
---
## XmlNodeReader::ReadAttributeValue() メソッド

属性値を 1 つ以上の **[Text](../../../system.text/)**、**EntityReference**、または **EndEntity** ノードに解析します。

```cpp
bool System::Xml::XmlNodeReader::ReadAttributeValue() override
```

### 戻り値

**true** は、返すノードがある場合です。 **false** は、最初の呼び出し時にリーダーが属性ノード上に位置していない場合、またはすべての属性値が読み取られた場合です。 **misc=\"\"** のような空属性は、[String::Empty](../../../system/string/empty/) の値を持つ単一ノードで **true** を返します。

## 参照

* クラス [XmlNodeReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)