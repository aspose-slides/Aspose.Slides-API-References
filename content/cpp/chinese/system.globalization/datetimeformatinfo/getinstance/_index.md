---
title: GetInstance()
second_title: Aspose.Slides for C++ API 参考
description: 获取与格式提供程序关联的格式化程序。
type: docs
weight: 846
url: /zh/system.globalization/datetimeformatinfo/getinstance/
---
## DateTimeFormatInfo::GetInstance(const IFormatProviderPtr\&) 方法

获取与格式提供程序关联的格式化程序。

```cpp
static DateTimeFormatInfoPtr System::Globalization::DateTimeFormatInfo::GetInstance(const IFormatProviderPtr &provider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| provider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | 用于获取格式的提供程序。 |

### 返回值

与格式提供程序关联的格式化程序，若不可用则返回当前线程的格式。

## 另见

* 类型定义 [DateTimeFormatInfoPtr](../../datetimeformatinfoptr/)
* 类型定义 [IFormatProviderPtr](../../../system/iformatproviderptr/)
* 类 [DateTimeFormatInfo](../)
* 命名空间 [System::Globalization](../../)
* 库 [Aspose.Slides](../../../)