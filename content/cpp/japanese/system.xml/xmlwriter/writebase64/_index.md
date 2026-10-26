---
title: WriteBase64()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、指定されたバイナリバイト列を Base64 にエンコードし、その結果のテキストを書き出します。
type: docs
weight: 300
url: /ja/system.xml/xmlwriter/writebase64/
---
## XmlWriter::WriteBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) メソッド

派生クラスでオーバーライドされた場合、指定されたバイナリバイト列を Base64 にエンコードし、その結果のテキストを書き出します。

```cpp
virtual void System::Xml::XmlWriter::WriteBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Byte](../../../system/byte/) 配列をエンコードします。 |
| index | **int32_t** | バッファ内で書き込むバイトの開始位置を示す位置。 |
| count | **int32_t** | 書き込むバイト数。 |

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [XmlWriter](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)