---
title: INotesSlideManager
second_title: Aspose.Slides for Java API Reference
description: Notes slide manager.
type: docs
url: /zh-hant/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

備註投影片管理員。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | 傳回目前投影片的備註投影片。 |
| [addNotesSlide()](#addNotesSlide--) | 傳回目前投影片的備註投影片，如果不存在則建立一個。 |
| [removeNotesSlide()](#removeNotesSlide--) | 移除目前投影片的備註投影片。 |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```

傳回目前投影片的備註投影片。 如果投影片沒有備註投影片，則傳回 null。 唯讀 [INotesSlide](../../com.aspose.slides/inotesslide)。

**傳回：**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```

傳回目前投影片的備註投影片，如果不存在則建立一個。

**傳回：**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) 此投影片的。
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```

移除目前投影片的備註投影片。