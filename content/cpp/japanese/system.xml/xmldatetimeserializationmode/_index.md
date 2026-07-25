---
title: XmlDateTimeSerializationMode
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列と DateTime の相互変換時に時間値をどのように扱うかを指定します。
type: docs
weight: 781
url: /ja/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode 列挙型

文字列と [DateTime](../../system/datetime/) の相互変換時に時間値をどのように扱うかを指定します。

```cpp
enum class XmlDateTimeSerializationMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Local | 0 | ローカル時間として扱います。[DateTime](../../system/datetime/) オブジェクトが協定世界時 (UTC) を表す場合、ローカル時間に変換されます。 |
| Utc | 1 | UTC として扱います。[DateTime](../../system/datetime/) オブジェクトがローカル時間を表す場合、UTC に変換されます。 |
| Unspecified | 2 | 文字列へ変換される場合、[DateTime](../../system/datetime/) はローカル時間として扱われます。文字列から [DateTime](../../system/datetime/) へ変換される場合、タイムゾーンが指定されていればローカル時間に変換されます。 |
| RoundtripKind | 3 | 変換時にタイムゾーン情報を保持すべきです。 |

## 参照

* 名前空間 [System::Xml](../)
* ライブラリ [Aspose.Slides](../../)