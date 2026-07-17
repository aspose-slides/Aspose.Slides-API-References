---
title: OperatingSystem
second_title: Aspose.Slides for C++ API 参考
description: "表示特定的操作系统并提供有关它的信息。此类的对象应仅使用 System::MakeObject() 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 1158
url: /zh/system/operatingsystem/
---
## OperatingSystem 类

表示特定的操作系统并提供有关它的信息。此类的对象应仅使用 [System::MakeObject()](../makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class OperatingSystem
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [PlatformID](../platformid/) [get_Platform](./get_platform/)() const | 返回当前对象所表示的操作系统的平台标识符。 |
| [String](../string/) [get_ServicePack](./get_servicepack/)() const | 返回当前对象所表示的操作系统的服务包名称。 |
| const [Version](../version/)\& [get_Version](./get_version/)() const | 返回一个常量引用，指向表示当前对象所表示的操作系统版本的 [Version](../version/) 对象。 |
| [String](../string/) [get_VersionString](./get_versionstring/)() const | 返回当前对象所表示的操作系统版本的字符串表示。 |
| static **bool** [IsFreeBSD](./isfreebsd/)() | 指示当前应用程序是否在 FreeBSD 上运行。 |
| static **bool** [IsLinux](./islinux/)() | 指示当前应用程序是否在 Linux 上运行。 |
| static **bool** [IsMacOS](./ismacos/)() | 指示当前应用程序是否在 MacOS 上运行。 |
| static **bool** [IsOSPlatform](./isosplatform/)(const [String](../string/)\&) | 指示当前应用程序是否在指定平台上运行。 |
| static **bool** [IsWindows](./iswindows/)() | 指示当前应用程序是否在 [Windows](../../system.windows/) 上运行。 |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&) | 构造一个实例，表示使用特定平台 ID 和版本指定的操作系统。 |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&, const [String](../string/)\&) | 构造一个实例，表示使用特定平台 ID、版本和服务包指定的操作系统。 |
| [String](../string/) [ToString](./tostring/)() const | 返回当前对象所表示的操作系统版本的字符串表示。 |

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)