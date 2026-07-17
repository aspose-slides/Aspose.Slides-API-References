---
title: IsNullOrEmpty()
second_title: Aspose.Slides C++ API 参考
description: 检查集合是否为 null 或为空。
type: docs
weight: 27
url: /zh/system/testtools/isnullarempty/
---
## TestTools::IsNullOrEmpty(const SharedPtr\<T\>\&) method

检查集合是否为 null 或为空。

```cpp
template<typename T> static bool System::TestTools::IsNullOrEmpty(const SharedPtr<T> &collection)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 集合类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | 要检查的集合。 |

### 返回值

如果集合为 null 或元素计数为零，则返回 true；否则返回 false。

## TestTools::IsNullOrEmpty(const System::String\&) method

检查字符串是否为 null 或为空。

```cpp
static bool System::TestTools::IsNullOrEmpty(const System::String &str)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) 用于检查。 |

### 返回值

如果字符串为 null 或长度为零，则返回 true；否则返回 false。

## 另见

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Struct [TestTools](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)