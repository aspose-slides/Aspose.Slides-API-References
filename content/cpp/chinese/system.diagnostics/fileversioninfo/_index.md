---
title: FileVersionInfo
second_title: Aspose.Slides for C++ API 参考
description: "提供文件版本信息。此类的对象只能使用 System::MakeObject() 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 1
url: /zh/system.diagnostics/fileversioninfo/
---
## FileVersionInfo 类

提供文件版本信息。此类的对象只能使用 [System::MakeObject()](../../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class FileVersionInfo
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [String](../../system/string/) [get_ProductVersion](./get_productversion/)() const | 获取产品版本字段。 |
| static [SharedPtr](../../system/sharedptr/)\<[System::Diagnostics::FileVersionInfo](./)\> [GetVersionInfo](./getversioninfo/)(const [String](../../system/string/)\&) | 获取文件版本信息；未实现。 |
## 另请参阅

* 命名空间 [System::Diagnostics](../)
* 库 [Aspose.Slides](../../)