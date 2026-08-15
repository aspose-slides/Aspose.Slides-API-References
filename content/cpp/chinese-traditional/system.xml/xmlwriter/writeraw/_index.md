---
title: WriteRaw()
second_title: Aspose.Slides for C++ API 參考文件
description: 在衍生類別中覆寫時，從字元緩衝區手動寫入原始標記。
type: docs
weight: 287
url: /zh-hant/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) 方法

When overridden in a derived class, writes raw markup manually from a character buffer.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 包含要寫入文字的字符陣列。 |
| index | **int32_t** | 緩衝區中指示寫入文字開始位置的索引。 |
| count | **int32_t** | 要寫入的字符數。 |

## XmlWriter::WriteRaw(const String\&) 方法

When overridden in a derived class, writes raw markup manually from a string.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) 包含要寫入的文字。 |

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)