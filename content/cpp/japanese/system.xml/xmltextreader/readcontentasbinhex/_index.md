---
title: ReadContentAsBinHex()
second_title: Aspose.Slides for C++ API リファレンス
description: コンテンツを読み取り、BinHex デコードされたバイナリバイトを返します。
type: docs
weight: 664
url: /ja/system.xml/xmltextreader/readcontentasbinhex/
---
## XmlTextReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) メソッド


コンテンツを読み取り、**BinHex** デコードされたバイナリバイトを返します。

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 結果のテキストをコピーするバッファ。この値は **nullptr** にできません。 |
| index | **int32_t** | 結果のコピーを開始するバッファ内のオフセット。 |
| count | **int32_t** | バッファにコピーする最大バイト数。このメソッドからは実際にコピーされたバイト数が返されます。 |

### 戻り値

バッファに書き込まれたバイト数。

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [XmlTextReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)