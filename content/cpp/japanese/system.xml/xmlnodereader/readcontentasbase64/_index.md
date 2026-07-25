---
title: ReadContentAsBase64()
second_title: Aspose.Slides for C++ API リファレンス
description: コンテンツを読み取り、Base64 デコードされたバイナリ バイトを返します。
type: docs
weight: 443
url: /ja/system.xml/xmlnodereader/readcontentasbase64/
---
## XmlNodeReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) メソッド

コンテンツを読み取り、Base64 デコードされたバイナリ バイトを返します。

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 結果のテキストをコピーするバッファ。 この値は **nullptr** にできません。 |
| index | **int32_t** | 結果のコピーを開始するバッファ内のオフセット。 |
| count | **int32_t** | バッファにコピーする最大バイト数。 実際にコピーされたバイト数はこのメソッドの戻り値です。 |

### 戻り値

バッファに書き込まれたバイト数。

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [XmlNodeReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)