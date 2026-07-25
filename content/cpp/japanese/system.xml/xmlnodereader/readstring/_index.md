---
title: ReadString()
second_title: Aspose.Slides for C++ API リファレンス
description: 要素またはテキストノードの内容を文字列として読み取ります。
type: docs
weight: 391
url: /ja/system.xml/xmlnodereader/readstring/
---
## XmlNodeReader::ReadString() メソッド

要素またはテキストノードの内容を文字列として読み取ります。

```cpp
String System::Xml::XmlNodeReader::ReadString() override
```

### 戻り値

要素またはテキストに類似したノードの内容（CDATA、[Text](../../../system.text/) ノードなどを含むことがあります）。リーダーが要素やテキストノード以外に位置している場合や、現在のコンテキストで返すテキストコンテンツが残っていない場合は空文字列になることがあります。注: テキストノードは要素テキストノードまたは属性テキストノードのいずれかです。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlNodeReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)