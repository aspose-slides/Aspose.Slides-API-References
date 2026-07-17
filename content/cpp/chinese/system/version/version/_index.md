---
title: Version()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个实例，表示指定的主版本、次版本、生成号和修订号。
type: docs
weight: 1
url: /zh/system/version/version/
---
## Version::Version(int, int, int, int) 构造函数

构造一个实例，表示指定的主版本、次版本、生成号和修订号。

```cpp
System::Version::Version(int major, int minor, int build, int revision)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| major | int | 主版本号 |
| minor | int | 次版本号 |
| build | int | 生成号 |
| revision | int | 修订号 |

## Version::Version(int, int, int) 构造函数

构造一个实例，表示指定的主版本、次版本和生成号。

```cpp
System::Version::Version(int major, int minor, int build)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| major | int | 主版本号 |
| minor | int | 次版本号 |
| build | int | 生成号 |

## Version::Version(int, int) 构造函数

构造一个实例，表示指定的主版本和次版本。

```cpp
System::Version::Version(int major, int minor)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| major | int | 主版本号 |
| minor | int | 次版本号 |

## Version::Version(const String\&) 构造函数

构造一个实例，表示以字符串形式表示的版本号。

```cpp
System::Version::Version(const String &version)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| version | const [String](../../string/)\& | 包含版本号的字符串 |

## Version::Version() 构造函数

构造一个实例，表示版本号 0.0.-1.-1。

```cpp
System::Version::Version()
```

## 另请参阅

* 类 [Version](../)
* 类 [String](../../string/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)