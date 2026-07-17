---
title: ToArray()
second_title: Aspose.Slides C++ API 参考
description: 创建并返回一个包含此规则所有回退字体的数组。
type: docs
weight: 144
url: /zh/aspose.slides/fontfallbackrule/toarray/
---
## FontFallBackRule::ToArray() 方法

创建并返回一个包含此规则所有回退字体的数组。

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray() override
```

### 返回值

Array of [System::String](../../../system/string/)
## 备注

```cpp
// 创建一个包含字体列表的规则。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// 将所有字体名称获取为数组。
ArrayPtr<String> fontNames = newRule->ToArray();
```

## FontFallBackRule::ToArray(int32_t, int32_t) 方法

创建并返回一个包含列表中指定范围内所有回退字体的数组。

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray(int32_t startIndex, int32_t count) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | **int32_t** | 要添加的第一个字体的索引。 |
| count | **int32_t** | 要添加的字体数量。 |

### 返回值

Array of [System::String](../../../system/string/)
## 备注

```cpp
// 创建一个包含字体列表的规则。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// 获取最后两个字体名称为数组。
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## 另请参阅

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [FontFallBackRule](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)