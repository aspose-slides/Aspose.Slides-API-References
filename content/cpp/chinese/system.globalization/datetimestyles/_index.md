---
title: DateTimeStyles
second_title: Aspose.Slides for C++ API 参考
description: 定义日期和时间的格式选项。位标志。
type: docs
weight: 456
url: /zh/system.globalization/datetimestyles/
---
## DateTimeStyles 枚举

定义日期和时间的格式选项。位标志。

```cpp
enum class DateTimeStyles : int32_t
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 默认。 |
| AllowLeadingWhite | 1 | 忽略前导空白。 |
| AllowTrailingWhite | 2 | 忽略尾随空白。 |
| AllowInnerWhite | 4 | 忽略内部空白。 |
| AllowWhiteSpaces | n/a | 忽略所有空白。 |
| NoCurrentDateDefault | 8 | 在解析日期/时间字符串时，如果年份/月份/日期全部缺失，默认日期设为 0001/1/1，而不是当前年份/月份/日期。 |
| AdjustToUniversal | 16 | 在解析日期/时间字符串时，如果存在时区说明符（"GMT","Z","+xxxx","-xxxx"），我们将根据 GMT 调整解析后的时间。 |
| AssumeLocal | 32 | 如果未提供时区，则使用本地时区。 |
| AssumeUniversal | 64 | 如果未提供时区，则使用 UTC。 |
| RoundtripKind | 128 | 尝试保留输入是未指定、本地还是 UTC。 |

## 另请参阅

* 命名空间 [System::Globalization](../)
* 库 [Aspose.Slides](../../)