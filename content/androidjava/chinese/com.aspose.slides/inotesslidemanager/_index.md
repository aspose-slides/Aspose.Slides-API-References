---
title: INotesSlideManager
second_title: Aspose.Slides for Android via Java API Reference
description: Notes slide manager.
type: docs
url: /zh/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

备注幻灯片管理器。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | 返回当前幻灯片的备注幻灯片。 |
| [addNotesSlide()](#addNotesSlide--) | 返回当前幻灯片的备注幻灯片，如果不存在则创建一个。 |
| [removeNotesSlide()](#removeNotesSlide--) | 移除当前幻灯片的备注幻灯片。 |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```

返回当前幻灯片的备注幻灯片。如果幻灯片没有备注幻灯片，则返回 null。只读 [INotesSlide](../../com.aspose.slides/inotesslide)。

**返回：**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```

返回当前幻灯片的备注幻灯片，如果不存在则创建一个。

**返回：**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) 用于此幻灯片。
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```

移除当前幻灯片的备注幻灯片。