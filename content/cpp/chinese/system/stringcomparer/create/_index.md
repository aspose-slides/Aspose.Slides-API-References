---
title: Create()
second_title: Aspose.Slides for C++ API 参考
description: 创建特定文化的比较器。
type: docs
weight: 79
url: /zh/system/stringcomparer/create/
---
## StringComparer::Create(const System::SharedPtr\<System::Globalization::CultureInfo\>\&, bool) 方法

创建特定文化的比较器。

```cpp
static StringComparerPtr System::StringComparer::Create(const System::SharedPtr<System::Globalization::CultureInfo> &culture, bool ignoreCase)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| culture | const [System::SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 用于创建比较器的文化。 |
| ignoreCase | **bool** | 指示比较器是否应忽略大小写。 |

### 返回值

指向新创建的比较器对象的指针。

## 另请参见

* 类型定义 [StringComparerPtr](../../stringcomparerptr/)
* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 类 [StringComparer](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)