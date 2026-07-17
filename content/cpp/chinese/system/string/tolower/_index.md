---
title: ToLower()
second_title: Aspose.Slides for C++ API 参考
description: 将所有字符串的字符转换为小写。
type: docs
weight: 547
url: /zh/system/string/tolower/
---
## String::ToLower() const 方法

将 string 的所有字符转换为小写。

```cpp
String System::String::ToLower() const
```

### 返回值

转换后的 string。

## String::ToLower(const SharedPtr\<System::Globalization::CultureInfo\>\&) const 方法

使用特定区域性将 string 的所有字符转换为小写。

```cpp
String System::String::ToLower(const SharedPtr<System::Globalization::CultureInfo> &cultureInfo) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cultureInfo | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 要使用的区域性。 |

### 返回值

转换后的 string。

## 另请参见

* Typedef [SharedPtr](../../sharedptr/)
* 类 [String](../)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)