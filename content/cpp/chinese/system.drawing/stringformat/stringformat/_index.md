---
title: StringFormat()
second_title: Aspose.Slides for C++ API 参考
description: 构造 StringFormat 类的新实例。
type: docs
weight: 1
url: /zh/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() 构造函数

构造 [StringFormat](../) 类的新实例。

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) 构造函数

使用指定的格式标志和语言构造 [StringFormat](../) 类的新实例。

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | 指定由被创建对象表示的字符串格式的 StringFormatFlags 枚举值的按位组合 |
| language | **int32_t** | 文本的语言 |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) 构造函数

复制构造函数。

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | 要复制的 [StringFormat](../) 对象 |

## 另请参见

* 枚举 [StringFormatFlags](../../stringformatflags/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [StringFormat](../)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)