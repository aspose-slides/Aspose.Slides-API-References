---
title: INotesSlideManager
second_title: Aspose.Slides for Android via Java API Reference
description: 註記投影片管理器。
type: docs
url: /zh-hant/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

註記投影片管理器。
## 方法

| Method | 說明 |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | 返回目前投影片的註記投影片。 |
| [addNotesSlide()](#addNotesSlide--) | 返回目前投影片的註記投影片，如果不存在則會建立一個。 |
| [removeNotesSlide()](#removeNotesSlide--) | 移除目前投影片的註記投影片。 |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```

返回目前投影片的註記投影片。如果投影片沒有註記投影片，則返回 null。唯讀 [INotesSlide](../../com.aspose.slides/inotesslide)。

**返回:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```

返回目前投影片的註記投影片，如果不存在則會建立一個。

**返回:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) 此投影片。

### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```

移除目前投影片的註記投影片。