---
title: GetCompareInfo()
second_title: Aspose.Slides for C++ API 参考
description: 获取与指定区域性关联的 CompareInfo，并使用指定程序集中的字符串比较方法。
type: docs
weight: 183
url: /zh/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr\<Reflection::Assembly\>\&) method

获取与指定区域性关联的 [CompareInfo](../)，并使用指定程序集中的字符串比较方法。

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| culture | int | Culture identifier (LCID). |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Assembly that contains string comparison methods. |

### 返回值

[CompareInfo](../) 对象。

## CompareInfo::GetCompareInfo(const String\&, const SharedPtr\<Reflection::Assembly\>\&) method

获取与指定区域性关联的 [CompareInfo](../)，并使用指定程序集中的字符串比较方法。

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Culture name. |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Assembly that contains string comparison methods. |

### 返回值

[CompareInfo](../) 对象。

## CompareInfo::GetCompareInfo(int) method

获取与指定区域性关联的 [CompareInfo](../)。

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| culture | int | Culture identifier (LCID). |

### 返回值

[CompareInfo](../) 对象。

## CompareInfo::GetCompareInfo(const String\&) method

获取与指定区域性关联的 [CompareInfo](../)。

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Culture name. |

### 返回值

[CompareInfo](../) 对象。

## 另请参见

* 类型定义 [CompareInfoPtr](../../compareinfoptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Assembly](../../../system.reflection/assembly/)
* 类 [CompareInfo](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Globalization](../../)
* 库 [Aspose.Slides](../../../)