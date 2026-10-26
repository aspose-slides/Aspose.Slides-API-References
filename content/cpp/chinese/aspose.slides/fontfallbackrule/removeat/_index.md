---
title: RemoveAt()
second_title: Aspose.Slides C++ API 参考
description: 从列表中删除指定索引处的回退字体。
type: docs
weight: 131
url: /zh/aspose.slides/fontfallbackrule/removeat/
---
## FontFallBackRule::RemoveAt(int32_t) 方法


从列表中删除指定索引处的回退字体。

```cpp
void Aspose::Slides::FontFallBackRule::RemoveAt(int32_t index) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 要删除的字体的零基索引。 |
## 备注



```cpp
// 创建一个包含字体列表的规则.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//从列表中移除 Tahoma.
newRule->RemoveAt(2);
```


## 另见

* 类 [FontFallBackRule](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)