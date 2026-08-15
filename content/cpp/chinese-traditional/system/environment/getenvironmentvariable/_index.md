---
title: GetEnvironmentVariable()
second_title: Aspose.Slides for C++ API 參考
description: 返回與目前程序相關聯之指定環境變數的值。
type: docs
weight: 287
url: /zh-hant/system/environment/getenvironmentvariable/
---
## Environment::GetEnvironmentVariable(const String\&) 方法

返回與目前程序相關聯之指定環境變數的值。

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| variable | const [String](../../string/)\& | 包含要檢索的變數名稱之字串 |

### 返回值

指定變數的值

## Environment::GetEnvironmentVariable(const String\&, EnvironmentVariableTarget) 方法

返回指定位置之指定環境變數的值。

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable, EnvironmentVariableTarget target)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| variable | const [String](../../string/)\& | 包含要檢索的變數名稱之字串 |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | 變數所在的位置 |

### 返回值

指定變數的值

## 另見

* 列舉 [EnvironmentVariableTarget](../../environmentvariabletarget/)
* 類別 [String](../../string/)
* 結構 [Environment](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)