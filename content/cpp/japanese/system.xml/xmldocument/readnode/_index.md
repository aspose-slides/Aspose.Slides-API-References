---
title: ReadNode()
second_title: Aspose.Slides for C++ API リファレンス
description: XmlReader の情報に基づいて XmlNode オブジェクトを作成します。リーダーはノードまたは属性上に位置している必要があります。
type: docs
weight: 495
url: /ja/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) メソッド

[XmlNode](../../xmlnode/)オブジェクトを[XmlReader](../../xmlreader/)の情報に基づいて作成します。リーダーはノードまたは属性上に位置している必要があります。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | XML ソース。 |

### 戻り値

新しい[XmlNode](../../xmlnode/)または、これ以上ノードが存在しない場合は**nullptr**です。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)