---
title: IsTest()
second_title: Aspose.Slides for C++ API 參考文件
description: 檢查測試方法是否存在。
type: docs
weight: 1
url: /zh-hant/system/testtoolsext/istest/
---
## TestToolsExt::IsTest(const char *, const char *, const char *) 方法


檢查測試方法是否存在。

```cpp
static bool System::TestToolsExt::IsTest(const char *name_space, const char *class_name, const char *method_name)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| name_space | const char * | 要查找的命名空間。 |
| class_name | const char * | 要查找的類別。 |
| method_name | const char * | 要查找的方法。 |

### 回傳值

True if test method is registered, false otherwise.

## TestToolsExt::IsTest(const char *, const char *) 方法


檢查測試方法是否存在。

```cpp
static bool System::TestToolsExt::IsTest(const char *class_name, const char *method_name)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| class_name | const char * | 要查找的類別。 |
| method_name | const char * | 要查找的方法。 |

### 回傳值

True if test method is registered, false otherwise.

## 另請參閱

* 結構 [TestToolsExt](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)