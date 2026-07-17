---
title: RemoveAt()
second_title: Aspose.Slides C++ API 参考
description: 移除列表中指定索引处的回退字体。
type: docs
weight: 92
url: /zh/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule::RemoveAt(int32_t) 方法

移除列表中指定索引处的回退字体。

```cpp
virtual void Aspose::Slides::IFontFallBackRule::RemoveAt(int32_t index)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 要移除的字体的零基索引。 |

## 备注

```cpp
// 创建一个包含字体列表的规则。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// 从列表中移除 Tahoma。
newRule->RemoveAt(2);
```

## 另请参见

* 类 [IFontFallBackRule](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)