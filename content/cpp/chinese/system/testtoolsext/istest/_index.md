---
title: IsTest()
second_title: Aspose.Slides for C++ API 参考
description: 检查测试方法是否存在。
type: docs
weight: 1
url: /zh/system/testtoolsext/istest/
---
## TestToolsExt::IsTest(const char *, const char *, const char *) 方法

检查测试方法是否存在。

```cpp
static bool System::TestToolsExt::IsTest(const char *name_space, const char *class_name, const char *method_name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name_space | const char * | 要查找的命名空间。 |
| class_name | const char * | 要查找的类。 |
| method_name | const char * | 要查找的方法。 |

### 返回值

如果已注册测试方法则返回 true，否则返回 false。

## TestToolsExt::IsTest(const char *, const char *) 方法

检查测试方法是否存在。

```cpp
static bool System::TestToolsExt::IsTest(const char *class_name, const char *method_name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| class_name | const char * | 要查找的类。 |
| method_name | const char * | 要查找的方法。 |

### 返回值

如果已注册测试方法则返回 true，否则返回 false。

## 另请参见

* Struct [TestToolsExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)