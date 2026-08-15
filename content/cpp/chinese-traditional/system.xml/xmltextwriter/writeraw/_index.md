---
title: WriteRaw()
second_title: Aspose.Slides for C++ API 參考
description: 從字元緩衝區手動寫入原始標記。
type: docs
weight: 417
url: /zh-hant/system.xml/xmltextwriter/writeraw/
---
## XmlTextWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) 方法

從字元緩衝區手動寫入原始標記。

```cpp
void System::Xml::XmlTextWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 包含要寫入文字的字元陣列。 |
| index | **int32_t** | 緩衝區中指示要寫入文字起始位置的索引。 |
| count | **int32_t** | 要寫入的字元數量。 |

## XmlTextWriter::WriteRaw(const String\&) 方法

從字串手動寫入原始標記。

```cpp
void System::Xml::XmlTextWriter::WriteRaw(const String &data) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) 包含要寫入的文字。 |

## 另請參閱

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [XmlTextWriter](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)