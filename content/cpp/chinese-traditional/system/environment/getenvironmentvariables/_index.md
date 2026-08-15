---
title: GetEnvironmentVariables()
second_title: Aspose.Slides for C++ API 參考手冊
description: 返回一個字典，包含與目前程序相關的所有環境變數名稱及其值。
type: docs
weight: 326
url: /zh-hant/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() 方法

返回一個字典，包含與目前程序相關的所有環境變數名稱及其值。

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) 方法

返回一個字典，包含指定位置的所有環境變數名稱及其值。

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | 變數所在的位置 |

### 返回值

一個字典，包含指定位置的所有環境變數名稱及其值

## 另請參見

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* 類別 [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* 類別 [String](../../string/)
* Struct [Environment](../)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)