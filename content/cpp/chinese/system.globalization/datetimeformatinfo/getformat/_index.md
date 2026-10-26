---
title: GetFormat()
second_title: Aspose.Slides for C++ API 参考
description: 获取特定类型的格式化程序。
type: docs
weight: 14
url: /zh/system.globalization/datetimeformatinfo/getformat/
---
## DateTimeFormatInfo::GetFormat(const TypeInfo\&) 方法

获取特定类型的格式化程序。

```cpp
SharedPtr<Object> System::Globalization::DateTimeFormatInfo::GetFormat(const TypeInfo &format_type) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| format_type | const [TypeInfo](../../../system/typeinfo/)\& | 获取的格式化程序的类型；仅支持 [DateTimeFormatInfo](../) 类型。 |

### 返回值

如果不可用，则返回 Formatter 或 null。

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [TypeInfo](../../../system/typeinfo/)
* 类 [DateTimeFormatInfo](../)
* 命名空间 [System::Globalization](../../)
* 库 [Aspose.Slides](../../../)