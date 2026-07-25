---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides for C++ API リファレンス
description: 要素を読み取り、Base64 コンテンツをデコードします。
type: docs
weight: 469
url: /ja/system.xml/xmlnodereader/readelementcontentasbase64/
---
## XmlNodeReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) メソッド

要素を読み取り、Base64 コンテンツをデコードします。

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 結果のテキストをコピーするバッファです。この値は **nullptr** にできません。 |
| index | **int32_t** | 結果のコピーを開始するバッファ内のオフセットです。 |
| count | **int32_t** | バッファにコピーする最大バイト数です。実際にコピーされたバイト数はこのメソッドから返されます。 |

### 戻り値

バッファに書き込まれたバイト数。

## 関連項目

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [XmlNodeReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)