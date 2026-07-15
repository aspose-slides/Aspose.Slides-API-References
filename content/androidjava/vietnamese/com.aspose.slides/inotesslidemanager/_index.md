---
title: INotesSlideManager
second_title: Aspose.Slides for Android via Java API Reference
description: Trình quản lý slide ghi chú.
type: docs
url: /vi/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

Trình quản lý slide ghi chú.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Returns the notes slide for the current slide. |
| [addNotesSlide()](#addNotesSlide--) | Returns the notes slide for the current slide, creating one if there isn't. |
| [removeNotesSlide()](#removeNotesSlide--) | Removes notes slide of the current slide. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```


Trả về slide ghi chú cho slide hiện tại. Trả về null nếu slide không có slide ghi chú. Chỉ đọc [INotesSlide](../../com.aspose.slides/inotesslide).

**Trả về:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```


Trả về slide ghi chú cho slide hiện tại, tạo một slide nếu không có.

**Trả về:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) cho slide này.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```


Xóa slide ghi chú của slide hiện tại.