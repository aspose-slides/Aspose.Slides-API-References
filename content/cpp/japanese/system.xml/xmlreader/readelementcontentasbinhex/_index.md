---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides for C++ API リファレンス
description: 要素を読み取り、BinHex コンテンツをデコードします。
type: docs
weight: 794
url: /ja/system.xml/xmlreader/readelementcontentasbinhex/
---
## XmlReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) メソッド

要素を読み取り、**BinHex** コンテンツをデコードします。

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 結果のテキストをコピーするためのバッファーです。この値は **nullptr** にできません。 |
| index | **int32_t** | 結果のコピーを開始するバッファー内のオフセットです。 |
| count | **int32_t** | バッファーにコピーする最大バイト数です。実際にコピーされたバイト数はこのメソッドから返されます。 |

### 戻り値

バッファーに書き込まれたバイト数です。

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [XmlReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)