---
title: ReadContentAsBinHex()
second_title: Aspose.Slides for C++ API リファレンス
description: コンテンツを読み取り、BinHex デコードされたバイナリバイトを返します。
type: docs
weight: 599
url: /ja/system.xml/xmlvalidatingreader/readcontentasbinhex/
---
## XmlValidatingReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) メソッド

コンテンツを読み取り、BinHex デコードされたバイナリバイトを返します。

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 結果のテキストをコピーするバッファ。この値は **nullptr** にできません。 |
| index | **int32_t** | バッファ内で結果のコピーを開始するオフセット。 |
| count | **int32_t** | バッファにコピーする最大バイト数。実際にコピーされたバイト数はこのメソッドから返されます。 |

### 戻り値

バッファに書き込まれたバイト数。

## 関連項目

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [XmlValidatingReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)