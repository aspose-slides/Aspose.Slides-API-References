---
title: Remove()
second_title: Aspose.Slides C++ API 参考
description: 从列表中删除特定回退字体的首次出现。
type: docs
weight: 79
url: /zh/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule::Remove(System::String) 方法

从列表中删除特定回退字体的首次出现。

```cpp
virtual void Aspose::Slides::IFontFallBackRule::Remove(System::String fontName)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | 要从列表中移除的字体名称。 |
## 备注

```cpp
// 创建一个包含字体列表的规则。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// 从列表中移除 Tahoma
newRule->Remove(u"Tahoma");
```

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [IFontFallBackRule](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)