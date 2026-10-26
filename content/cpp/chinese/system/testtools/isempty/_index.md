---
title: IsEmpty()
second_title: Aspose.Slides for C++ API 参考
description: 检查字符串是否为空。
type: docs
weight: 14
url: /zh/system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) 方法

检查字符串是否为空。

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) 用于检查是否为空。 |

### 返回值

如果字符串为空（null-length），则返回 true；否则返回 false。

## TestTools::IsEmpty(const SharedPtr\<T\>\&) 方法

检查集合是否为空。

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 集合类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | 用于检查的集合。 |

### 返回值

如果集合的元素计数为零，则返回 true；否则返回 false。

## 另请参阅

* Typedef [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* Struct [TestTools](../)
* 命名空间 [System](../../)
* Library [Aspose.Slides](../../../)