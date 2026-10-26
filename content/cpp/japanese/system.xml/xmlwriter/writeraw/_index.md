---
title: WriteRaw()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、文字バッファから生のマークアップを手動で書き込みます。
type: docs
weight: 287
url: /ja/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) メソッド

派生クラスでオーバーライドされた場合、文字バッファから生のマークアップを手動で書き込みます。

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 書き込むテキストを含む文字配列。 |
| index | **int32_t** | バッファ内で書き込むテキストの開始位置を示す位置。 |
| count | **int32_t** | 書き込む文字数。 |

## XmlWriter::WriteRaw(const String\&) メソッド

派生クラスでオーバーライドされた場合、文字列から生のマークアップを手動で書き込みます。

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) 書き込むテキストを含む。 |

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [XmlWriter](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)