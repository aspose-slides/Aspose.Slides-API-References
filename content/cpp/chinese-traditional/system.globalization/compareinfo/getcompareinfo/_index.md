---
title: GetCompareInfo()
second_title: Aspose.Slides for C++ API 參考
description: 取得與指定文化關聯的 CompareInfo，並使用指定組件中的字串比較方法。
type: docs
weight: 183
url: /zh-hant/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr\<Reflection::Assembly\>\&) 方法

取得與指定文化關聯的 [CompareInfo](../)，並使用指定組件中的字串比較方法。

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| culture | int | 文化識別碼 (LCID)。 |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | 包含字串比較方法的程序集。 |

### 返回值

[CompareInfo](../) 物件。

## CompareInfo::GetCompareInfo(const String\&, const SharedPtr\<Reflection::Assembly\>\&) 方法

取得與指定文化關聯的 [CompareInfo](../)，並使用指定組件中的字串比較方法。

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 文化名稱。 |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | 包含字串比較方法的程序集。 |

### 返回值

[CompareInfo](../) 物件。

## CompareInfo::GetCompareInfo(int) 方法

取得與指定文化關聯的 [CompareInfo](../)。

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| culture | int | 文化識別碼 (LCID)。 |

### 返回值

[CompareInfo](../) 物件。

## CompareInfo::GetCompareInfo(const String\&) 方法

取得與指定文化關聯的 [CompareInfo](../)。

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 文化名稱。 |

### 返回值

[CompareInfo](../) 物件。

## 另請參閱

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Assembly](../../../system.reflection/assembly/)
* Class [CompareInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)