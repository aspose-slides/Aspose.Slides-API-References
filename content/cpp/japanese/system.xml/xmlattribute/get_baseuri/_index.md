---
title: get_BaseURI()
second_title: Aspose.Slides for C++ API リファレンス
description: ノードのベースとなる統一リソース識別子 (URI) を返します。
type: docs
weight: 183
url: /ja/system.xml/xmlattribute/get_baseuri/
---
## XmlAttribute::get_BaseURI() メソッド


ノードのベースとなる統一リソース識別子 (URI) を返します。

```cpp
String System::Xml::XmlAttribute::get_BaseURI() override
```


### 戻り値

ノードが読み込まれた場所、またはノードにベース URI がない場合は [String::Empty](../../../system/string/empty/) です。 [Attribute](../../../system/attribute/) ノードは所有要素と同じベース URI を持ちます。 属性ノードに所有要素がない場合、get_BaseURI は [String::Empty](../../../system/string/empty/) を返します。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlAttribute](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)