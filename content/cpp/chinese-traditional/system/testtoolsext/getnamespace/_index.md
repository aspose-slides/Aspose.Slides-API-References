---
title: GetNamespace()
second_title: Aspose.Slides for C++ API 參考
description: 取得指定測試的命名空間。
type: docs
weight: 14
url: /zh-hant/system/testtoolsext/getnamespace/
---
## TestToolsExt::GetNamespace(const char *, const char *, std::string\&) 方法

取得指定測試的命名空間。

```cpp
static bool System::TestToolsExt::GetNamespace(const char *class_name, const char *method_name, std::string &name_space)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| class_name | const char * | 要搜尋的類別。 |
| method_name | const char * | 要搜尋的方法。 |
| name_space | std::string\& | 若找到，放入命名空間名稱的變數。 |

### 返回值

如果找到測試方法則返回 True，否則返回 false。

## 另見

* Struct [TestToolsExt](../)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)