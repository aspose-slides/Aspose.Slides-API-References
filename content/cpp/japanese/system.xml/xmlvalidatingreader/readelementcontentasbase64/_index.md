---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides for C++ API リファレンス
description: 要素を読み取り、Base64 コンテンツをデコードします。
type: docs
weight: 586
url: /ja/system.xml/xmlvalidatingreader/readelementcontentasbase64/
---
## XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

要素を読み取り、Base64 コンテンツをデコードします。

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 結果テキストをコピーするバッファです。この値は **nullptr** にできません。 |
| index | **int32_t** | 結果のコピーを開始するバッファ内のオフセットです。 |
| count | **int32_t** | バッファにコピーする最大バイト数です。コピーされた実際のバイト数はこのメソッドから返されます。 |

### 戻り値

バッファに書き込まれたバイト数です。

## 参照

* typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [XmlValidatingReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)