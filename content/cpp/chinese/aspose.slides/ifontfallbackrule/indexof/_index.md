---
title: IndexOf()
second_title: Aspose.Slides for C++ API 参考
description: 返回集合中指定规则的索引。
type: docs
weight: 118
url: /zh/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) 方法

返回集合中指定规则的索引。

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | 要查找的字体名称。 |

### 返回值

字体的索引；如果列表中未找到字体，则返回 -1。

## 备注



```cpp
// 创建一个包含字体列表的规则.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//获取 Tahoma 的索引
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```

## 另见

* 类 [String](../../../system/string/)
* 类 [IFontFallBackRule](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)