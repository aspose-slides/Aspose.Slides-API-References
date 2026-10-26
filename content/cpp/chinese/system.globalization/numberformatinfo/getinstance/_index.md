---
title: GetInstance()
second_title: Aspose.Slides C++ API 参考
description: 获取与格式提供程序关联的格式化程序。
type: docs
weight: 794
url: /zh/system.globalization/numberformatinfo/getinstance/
---
## NumberFormatInfo::GetInstance(const IFormatProviderPtr\&) 方法

获取与格式提供程序关联的格式化程序。

```cpp
static NumberFormatInfoPtr System::Globalization::NumberFormatInfo::GetInstance(const IFormatProviderPtr &provider)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| provider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | 用于获取格式的提供程序。 |

### 返回值

与格式提供程序关联的格式化程序，或在不可用时使用当前线程的格式。

## 另见

* Typedef [NumberFormatInfoPtr](../../numberformatinfoptr/)
* Typedef [IFormatProviderPtr](../../../system/iformatproviderptr/)
* Class [NumberFormatInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)