---
title: GetEnvironmentVariables()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个包含当前进程所有环境变量名称及其对应值的字典。
type: docs
weight: 326
url: /zh/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() 方法

Returns a dictionary containing all environment variables names and their values associated with the current process.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) 方法

Returns a dictionary containing all environment variables' names and their values from the specified location.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | 变量的位置 |

### 返回值

一个字典，其中包含来自指定位置的所有环境变量名称及其值

## 另请参阅

* 枚举 [EnvironmentVariableTarget](../../environmentvariabletarget/)
* 类 [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* 类 [String](../../string/)
* 结构体 [Environment](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)