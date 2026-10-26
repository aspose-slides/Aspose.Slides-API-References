---
title: ReadContentAsBase64()
second_title: Aspose.Slides for C++ API リファレンス
description: コンテンツを読み取り、Base64 デコードされたバイナリ バイトを返します。
type: docs
weight: 573
url: /ja/system.xml/xmlvalidatingreader/readcontentasbase64/
---
## XmlValidatingReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method


コンテンツを読み取り、Base64 デコードされたバイナリ バイトを返します。

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 結果のテキストをコピーするバッファです。この値は **nullptr** にできません。 |
| index | **int32_t** | 結果のコピーを開始するバッファ内のオフセットです。 |
| count | **int32_t** | バッファにコピーする最大バイト数です。実際にコピーされたバイト数はこのメソッドから返されます。 |

### 戻り値

バッファに書き込まれたバイト数です。

## 関連項目

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)