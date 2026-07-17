---
title: Add()
second_title: Aspose.Slides for C++ API 参考
description: 将 IMathBlock 添加到集合的末尾。
type: docs
weight: 14
url: /zh/aspose.slides.mathtext/imathblockcollection/add/
---
## IMathBlockCollection::Add(System::SharedPtr\<IMathBlock\>) 方法

将 [IMathBlock](../../imathblock/) 添加到集合的末尾。

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Add(System::SharedPtr<IMathBlock> item)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 将被添加到集合末尾的数学块 |

## 备注



示例：
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathBlock](../../imathblock/)
* 类 [IMathBlockCollection](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)