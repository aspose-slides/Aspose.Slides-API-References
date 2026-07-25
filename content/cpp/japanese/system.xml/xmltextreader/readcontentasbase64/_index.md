---
title: ReadContentAsBase64()
second_title: C++ 用 Aspose.Slides API リファレンス
description: コンテンツを読み取り、Base64 デコードされたバイナリバイトを返します。
type: docs
weight: 638
url: /ja/system.xml/xmltextreader/readcontentasbase64/
---
## XmlTextReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

コンテンツを読み取り、**Base64** デコードされたバイナリバイトを返します。

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 結果のテキストをコピーするバッファ。 この値は **nullptr** にできません。 |
| index | **int32_t** | 結果のコピーを開始するバッファ内のオフセット。 |
| count | **int32_t** | バッファにコピーする最大バイト数。 実際にコピーされたバイト数はこのメソッドから返されます。 |

### Return Value

バッファに書き込まれたバイト数。

## 関連項目

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [XmlTextReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)