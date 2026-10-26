---
title: GetNamespace()
second_title: Aspose.Slides for C++ API 参考
description: 检索指定测试的命名空间。
type: docs
weight: 14
url: /zh/system/testtoolsext/getnamespace/
---
## TestToolsExt::GetNamespace(const char *, const char *, std::string\&) 方法


检索指定测试的命名空间。

```cpp
static bool System::TestToolsExt::GetNamespace(const char *class_name, const char *method_name, std::string &name_space)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| class_name | const char * | 要查找的类。 |
| method_name | const char * | 要查找的方法。 |
| name_space | std::string\& | 用于存放命名空间名称的变量（如果找到）。 |

### 返回值

如果找到测试方法则返回 True，否则返回 false。

## 另请参见

* Struct [TestToolsExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)