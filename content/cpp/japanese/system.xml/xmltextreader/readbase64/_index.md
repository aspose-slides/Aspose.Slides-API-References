---
title: ReadBase64()
second_title: Aspose.Slides for C++ API リファレンス
description: Base64 をデコードし、デコードされたバイナリバイトを返します。
type: docs
weight: 768
url: /ja/system.xml/xmltextreader/readbase64/
---
## XmlTextReader::ReadBase64(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Base64 をデコードし、デコードされたバイナリバイトを返します。

```cpp
int32_t System::Xml::XmlTextReader::ReadBase64(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | テキスト内容が書き込まれるバッファとして機能する文字の配列です。 |
| offset | **int32_t** | メソッドがバッファへの書き込みを開始できる配列内のゼロベースインデックスです。 |
| len | **int32_t** | バッファに書き込むバイト数です。 |

### 戻り値

バッファに書き込まれたバイト数です。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)