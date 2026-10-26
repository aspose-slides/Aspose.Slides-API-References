---
title: ToArray()
second_title: Aspose.Slides for C++ API 参考
description: 创建并返回一个包含此规则所有 FallBack 字体的数组。
type: docs
weight: 105
url: /zh/aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() 方法

创建并返回一个包含此规则所有FallBack字体的数组。

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```

### 返回值

[System::String](../../../system/string/) 的数组

## 备注

```cpp
// 创建一个包含字体列表的规则。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// 获取所有字体名称为数组
ArrayPtr<String> fontNames = newRule->ToArray();
```

## IFontFallBackRule::ToArray(int32_t, int32_t) 方法

从列表中指定的范围创建并返回包含所有FallBack字体的数组。

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | **int32_t** | 要添加的第一个字体的索引。 |
| count | **int32_t** | 要添加的字体数量。 |

### 返回值

[System::String](../../../system/string/) 的数组

## 备注

```cpp
// 创建一个包含字体列表的规则。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// 获取最后两个字体名称为数组
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [IFontFallBackRule](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)