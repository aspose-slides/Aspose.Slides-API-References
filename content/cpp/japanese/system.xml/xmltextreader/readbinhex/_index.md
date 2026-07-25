---
title: ReadBinHex()
second_title: Aspose.Slides for C++ API リファレンス
description: BinHex をデコードし、デコードされたバイナリバイトを返します。
type: docs
weight: 781
url: /ja/system.xml/xmltextreader/readbinhex/
---
## XmlTextReader::ReadBinHex(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) メソッド

**BinHex** をデコードし、デコードされたバイナリバイトを返します。

```cpp
int32_t System::Xml::XmlTextReader::ReadBinHex(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | デコードされたバイナリバイトが書き込まれるバッファとして機能するバイト配列です。 |
| offset | **int32_t** | メソッドがバッファへの書き込みを開始できる位置を指定する、配列内のゼロベースインデックスです。 |
| len | **int32_t** | バッファに書き込むバイト数です。 |

### 戻り値

バッファに書き込まれたバイト数です。

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [XmlTextReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)