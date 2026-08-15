---
title: XmlDateTimeSerializationMode
second_title: Aspose.Slides for C++ API 參考
description: 指定在字串與 DateTime 之間轉換時如何處理時間值。
type: docs
weight: 781
url: /zh-hant/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode 列舉


指定在字串與 [DateTime](../../system/datetime/) 之間轉換時如何處理時間值。

```cpp
enum class XmlDateTimeSerializationMode
```

### 值

| 名稱 | 值 | 描述 |
| --- | --- | --- |
| Local | 0 | 視為本地時間。如果 [DateTime](../../system/datetime/) 物件代表協調世界時 (UTC)，則會轉換為本地時間。 |
| Utc | 1 | 視為 UTC。如果 [DateTime](../../system/datetime/) 物件代表本地時間，則會轉換為 UTC。 |
| Unspecified | 2 | 如果 [DateTime](../../system/datetime/) 正在轉換為字串，則視為本地時間。如果字串正在轉換為 [DateTime](../../system/datetime/)，則在指定時區時轉換為本地時間。 |
| RoundtripKind | 3 | 轉換時應保留時區資訊。 |

## 另請參閱

* 命名空間 [System::Xml](../)
* 函式庫 [Aspose.Slides](../../)