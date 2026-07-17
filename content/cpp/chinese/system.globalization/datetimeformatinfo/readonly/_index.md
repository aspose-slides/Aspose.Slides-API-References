---
title: ReadOnly()
second_title: Aspose.Slides C++ API 参考
description: 获取格式化程序的只读版本。
type: docs
weight: 859
url: /zh/system.globalization/datetimeformatinfo/readonly/
---
## DateTimeFormatInfo::ReadOnly(const DateTimeFormatInfoPtr\&) 方法

获取格式化程序的只读版本。

```cpp
static DateTimeFormatInfoPtr System::Globalization::DateTimeFormatInfo::ReadOnly(const DateTimeFormatInfoPtr &info)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| info | const [DateTimeFormatInfoPtr](../../datetimeformatinfoptr/)\& | 用于获取只读版本的格式化程序。 |

### 返回值

如果 **info** 为只读，则返回它；否则创建它的副本并标记为只读。

## 参见

* 类型定义 [DateTimeFormatInfoPtr](../../datetimeformatinfoptr/)
* 类 [DateTimeFormatInfo](../)
* 命名空间 [System::Globalization](../../)
* 库 [Aspose.Slides](../../../)