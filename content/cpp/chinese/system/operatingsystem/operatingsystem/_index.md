---
title: OperatingSystem()
second_title: Aspose.Slides C++ API 参考
description: 构造一个实例，用于表示指定的特定平台 ID 和版本的操作系统。
type: docs
weight: 1
url: /zh/system/operatingsystem/operatingsystem/
---
## OperatingSystem::OperatingSystem(PlatformID, const Version\&) 构造函数

构造一个实例，用于表示指定的特定平台标识和版本的操作系统。

```cpp
System::OperatingSystem::OperatingSystem(PlatformID platform, const Version &version)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| platform | [PlatformID](../../platformid/) | 将由正在构造的对象表示的操作系统的平台标识符 |
| version | const [Version](../../version/)\& | 将由正在构造的对象表示的操作系统的版本 |

## OperatingSystem::OperatingSystem(PlatformID, const Version\&, const String\&) 构造函数

构造一个实例，用于表示指定的特定平台标识、版本和服务包的操作系统。

```cpp
System::OperatingSystem::OperatingSystem(PlatformID platform, const Version &version, const String &service_pack)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| platform | [PlatformID](../../platformid/) | 将由正在构造的对象表示的操作系统的平台标识符 |
| version | const [Version](../../version/)\& | 将由正在构造的对象表示的操作系统的版本 |
| service_pack | const [String](../../string/)\& | 将由正在构造的对象表示的操作系统的服务包名称 |

## 另见

* 枚举 [PlatformID](../../platformid/)
* 类 [Version](../../version/)
* 类 [OperatingSystem](../)
* 类 [String](../../string/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)