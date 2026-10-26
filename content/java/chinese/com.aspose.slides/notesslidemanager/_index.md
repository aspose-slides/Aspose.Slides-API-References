---
title: NotesSlideManager
second_title: Aspose.Slides for Java API 参考
description: 备注幻灯片管理器。
type: docs
url: /zh/com.aspose.slides/notesslidemanager/
---
**继承:**
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

备注幻灯片管理器。

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // 实例化一个表示演示文件的 Presentation 对象
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // 向第一张幻灯片添加备注
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // 保存演示文稿到磁盘
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // 实例化一个表示演示文件的 Presentation 对象
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // 移除第一张幻灯片的备注
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // 保存演示文稿到磁盘
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 方法

| 方法 | 描述 |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | 返回当前幻灯片的备注幻灯片。 |
| [addNotesSlide()](#addNotesSlide--) | 返回当前幻灯片的备注幻灯片，如果不存在则创建。 |
| [removeNotesSlide()](#removeNotesSlide--) | 移除当前幻灯片的备注幻灯片。 |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```


返回当前幻灯片的备注幻灯片。如果幻灯片没有备注幻灯片则返回 null。只读 [INotesSlide](../../com.aspose.slides/inotesslide)。

**返回:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```


返回当前幻灯片的备注幻灯片，如果不存在则创建。

**返回:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) for this slide.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```


移除当前幻灯片的备注幻灯片。