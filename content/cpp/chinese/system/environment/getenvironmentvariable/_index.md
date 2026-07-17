---
title: GetEnvironmentVariable()
second_title: Aspose.Slides for C++ API 参考
description: 返回与当前进程关联的指定环境变量的值。
type: docs
weight: 287
url: /zh/system/environment/getenvironmentvariable/
---
## Environment::GetEnvironmentVariable(const String\&) 方法

返回与当前进程关联的指定环境变量的值。

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| variable | const [String](../../string/)\& | 包含要检索的变量名称的字符串 |

### 返回值

指定变量的值

## Environment::GetEnvironmentVariable(const String\&, EnvironmentVariableTarget) 方法

返回来自指定位置的指定环境变量的值。

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable, EnvironmentVariableTarget target)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| variable | const [String](../../string/)\& | 包含要检索的变量名称的字符串 |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | 变量的位置 |

### 返回值

指定变量的值

## 另请参阅

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* 类 [String](../../string/)
* Struct [Environment](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)