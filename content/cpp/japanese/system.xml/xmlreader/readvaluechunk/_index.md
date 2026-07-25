---
title: ReadValueChunk()
second_title: C++ 用 Aspose.Slides API リファレンス
description: XML ドキュメントに埋め込まれた大きなテキストストリームを読み取ります。
type: docs
weight: 807
url: /ja/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) method

XML ドキュメントに埋め込まれた大きなテキストストリームを読み取ります。

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | テキスト内容が書き込まれるバッファとして機能する文字配列。この値は **nullptr** にできません。 |
| index | **int32_t** | [XmlReader](../) が結果のコピーを開始できるバッファ内のオフセット。 |
| count | **int32_t** | バッファにコピーする最大文字数。実際にコピーされた文字数はこのメソッドの戻り値として返されます。 |

### 戻り値

バッファに読み取られた文字数。テキスト内容がもう無い場合は 0 が返されます。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)