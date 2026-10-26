---
title: ReadContentAsBinHex()
second_title: Aspose.Slides for C++ API リファレンス
description: コンテンツを読み取り、BinHex デコードされたバイナリ バイトを返します。
type: docs
weight: 456
url: /ja/system.xml/xmlnodereader/readcontentasbinhex/
---
## XmlNodeReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) method


コンテンツを読み取り、BinHex デコードされたバイナリ バイトを返します。

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 結果のテキストをコピーするバッファ。 この値は **nullptr** にできません。 |
| index | **int32_t** | 結果のコピーを開始するバッファ内のオフセット。 |
| count | **int32_t** | バッファにコピーするバイト数の最大値。 実際にコピーされたバイト数はこのメソッドから返されます。 |

### 戻り値

バッファに書き込まれたバイト数。

## 関連項目

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [XmlNodeReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)