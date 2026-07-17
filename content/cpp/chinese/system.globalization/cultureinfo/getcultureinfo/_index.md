---
title: GetCultureInfo()
second_title: Aspose.Slides for C++ API 参考
description: 根据名称获取区域性。等同于 CreateSpecificCulture.
type: docs
weight: 586
url: /zh/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) 方法

根据名称获取区域性。等同于 CreateSpecificCulture.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 预定义的区域性名称或现有区域性对象的名称。 |

### 返回值

新创建的区域性对象。

## CultureInfo::GetCultureInfo(const String\&, const String\&) 方法

根据名称获取区域性。

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 区域性名称。 |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | 用于 [TextInfo](../../textinfo/) 和 [CompareInfo](../../compareinfo/) 对象的区域性名称。 |

### 返回值

区域性对象。

## CultureInfo::GetCultureInfo(int32_t) 方法

根据 id 获取区域性。

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| culture | **int32_t** | 区域性标识符。 |

### 返回值

新创建的区域性对象。

## 另请参阅

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* 类 [String](../../../system/string/)
* 类 [CultureInfo](../)
* 命名空间 [System::Globalization](../../)
* Library [Aspose.Slides](../../../)