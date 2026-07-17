---
title: GetFormat()
second_title: Aspose.Slides for C++ API 参考
description: 获取特定类型的格式化程序。
type: docs
weight: 742
url: /zh/system.globalization/numberformatinfo/getformat/
---
## NumberFormatInfo::GetFormat(const TypeInfo\&) 方法

获取特定类型的格式化程序。

```cpp
SharedPtr<Object> System::Globalization::NumberFormatInfo::GetFormat(const TypeInfo &format_type) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format_type | const [TypeInfo](../../../system/typeinfo/)\& | 要获取的格式化程序类型；仅支持 [NumberFormatInfo](../) 类型。 |

### 返回值

Formatter 或 null（如果不可用）。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [TypeInfo](../../../system/typeinfo/)
* 类 [NumberFormatInfo](../)
* 命名空间 [System::Globalization](../../)
* 库 [Aspose.Slides](../../../)