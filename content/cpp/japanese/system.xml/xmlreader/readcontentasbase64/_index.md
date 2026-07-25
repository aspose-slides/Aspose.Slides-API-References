---
title: ReadContentAsBase64()
second_title: Aspose.Slides for C++ API リファレンス
description: コンテンツを読み取り、Base64 デコードされたバイナリバイトを返します。
type: docs
weight: 755
url: /ja/system.xml/xmlreader/readcontentasbase64/
---
## XmlReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) メソッド

結果の内容を読み取り、Base64 デコードされたバイナリバイトを返します。

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 結果のテキストをコピーするバッファ。この値は **nullptr** にできません。 |
| index | **int32_t** | バッファ内で結果のコピーを開始するオフセット。 |
| count | **int32_t** | バッファにコピーする最大バイト数。このメソッドから返されるのは実際にコピーされたバイト数です。 |

### 戻り値

バッファに書き込まれたバイト数です。

## 関連項目

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [XmlReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)