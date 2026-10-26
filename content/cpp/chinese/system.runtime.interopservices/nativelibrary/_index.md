---
title: NativeLibrary
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 40
url: /zh/system.runtime.interopservices/nativelibrary/
---
## NativeLibrary 类




```cpp
class NativeLibrary
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static void [Free](./free/)(IntPtr) | 卸载动态库。 |
| static IntPtr [GetExport](./getexport/)(IntPtr, const [String](../../system/string/)\&) | 获取给定库项的地址。 |
| static IntPtr [Load](./load/)(const [String](../../system/string/)\&) | 加载本机动态库。出错时抛出异常。 |
| static **bool** [TryLoad](./tryload/)(const [String](../../system/string/)\&, IntPtr\&) | 加载本机动态库。 |
## 另请参阅

* 命名空间 [System::Runtime::InteropServices](../)
* 库 [Aspose.Slides](../../)