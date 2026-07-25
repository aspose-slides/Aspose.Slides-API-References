---
title: ReadContentAsBinHex()
second_title: Aspose.Slides for C++ API リファレンス
description: コンテンツを読み取り、BinHex デコードされたバイナリバイトを返します。
type: docs
weight: 781
url: /ja/system.xml/xmlreader/readcontentasbinhex/
---
## XmlReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) メソッド

コンテンツを読み取り、**BinHex** デコードされたバイナリバイトを返します。

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 結果のテキストをコピーするバッファ。この値は **nullptr** にできません。 |
| index | **int32_t** | バッファ内で結果のコピーを開始するオフセット。 |
| count | **int32_t** | バッファにコピーするバイト数の最大値。このメソッドからは実際にコピーされたバイト数が返されます。 |

### 戻り値

バッファに書き込まれたバイト数。

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [XmlReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)