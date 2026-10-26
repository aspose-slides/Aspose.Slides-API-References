---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: 要素を読み取り、Base64 コンテンツをデコードします。
type: docs
weight: 651
url: /ja/system.xml/xmltextreader/readelementcontentasbase64/
---
## XmlTextReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) メソッド

要素を読み取り、Base64 コンテンツをデコードします。

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | コピー先のテキストを格納するバッファです。この値は **nullptr** にできません。 |
| index | **int32_t** | バッファ内で結果のコピーを開始するオフセットです。 |
| count | **int32_t** | バッファにコピーするバイト数の最大値です。実際にコピーされたバイト数はこのメソッドから返されます。 |

### 戻り値

バッファに書き込まれたバイト数です。

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [XmlTextReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)