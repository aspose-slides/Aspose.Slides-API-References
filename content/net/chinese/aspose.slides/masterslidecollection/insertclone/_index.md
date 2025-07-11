---
title: InsertClone
second_title: Aspose.Sildes for .NET API Reference
description: 将指定的主幻灯片的副本插入到集合的指定位置。链接的布局幻灯片也会被复制。
type: docs
weight: 80
url: /zh/aspose.slides/masterslidecollection/insertclone/
---

## MasterSlideCollection.InsertClone 方法

将指定的主幻灯片的副本插入到集合的指定位置。链接的布局幻灯片也会被复制。

```csharp
public IMasterSlide InsertClone(int index, IMasterSlide sourceMaster)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 新幻灯片的索引。 |
| sourceMaster | IMasterSlide | 要克隆的幻灯片。 |

### 返回值

插入的主幻灯片。

### 示例

以下示例演示如何在另一个 PowerPoint 演示文稿中克隆主幻灯片。

```csharp
[C#]
// 实例化 Presentation 类以加载源演示文稿文件
using (Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx"))
{
    // 实例化 Presentation 类以创建目标演示文稿（克隆幻灯片的地方）
    using (Presentation destPres = new Presentation())
    {
        // 从源演示文稿的幻灯片集合中实例化 ISlide 并获取
        // 主幻灯片
        ISlide SourceSlide = srcPres.Slides[0];
        IMasterSlide SourceMaster = SourceSlide.LayoutSlide.MasterSlide;
		// 获取目标演示文稿的主幻灯片
        IMasterSlideCollection masters = destPres.Masters;
        // 从源演示文稿的主幻灯片集合中克隆所需的主幻灯片到目标演示文稿的主集合中
        IMasterSlide iSlide = masters.AddClone(SourceMaster);
        // 目标演示文稿中的幻灯片集合
        ISlideCollection slds = destPres.Slides;
		// 将源幻灯片克隆到目标幻灯片集合中。
        slds.AddClone(SourceSlide, iSlide, true);
        // 将目标演示文稿保存到磁盘
        destPres.Save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
    }
}
```

### 另请参阅

* interface [IMasterSlide](../../imasterslide)
* class [MasterSlideCollection](../../masterslidecollection)
* namespace [Aspose.Slides](../../masterslidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->