---
title: XmlDateTimeSerializationMode
second_title: Aspose.Slides C++ API 参考
description: 指定在字符串和 DateTime 之间转换时如何处理时间值。
type: docs
weight: 781
url: /zh/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode 枚举

指定在字符串和 [DateTime](../../system/datetime/) 之间转换时如何处理时间值。

```cpp
enum class XmlDateTimeSerializationMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Local | 0 | 视为本地时间。如果 [DateTime](../../system/datetime/) 对象表示协调世界时 (UTC)，则会转换为本地时间。 |
| Utc | 1 | 视为 UTC。如果 [DateTime](../../system/datetime/) 对象表示本地时间，则会转换为 UTC。 |
| Unspecified | 2 | 如果将 [DateTime](../../system/datetime/) 转换为字符串，则视为本地时间。如果将字符串转换为 [DateTime](../../system/datetime/)，且指定了时区，则转换为本地时间。 |
| RoundtripKind | 3 | 转换时应保留时区信息。 |

## 另请参见

* 命名空间 [System::Xml](../)
* 库 [Aspose.Slides](../../)