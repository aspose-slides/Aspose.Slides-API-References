---
title: INotesSlideManager
second_title: Aspose.Slides for Java API Reference
description: Notes slide manager.
type: docs
url: /vi/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

Trình quản lý slide ghi chú.
## Phương thức

| Method | Description |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Trả về slide ghi chú của slide hiện tại. |
| [addNotesSlide()](#addNotesSlide--) | Trả về slide ghi chú của slide hiện tại, tạo mới nếu không tồn tại. |
| [removeNotesSlide()](#removeNotesSlide--) | Xóa slide ghi chú của slide hiện tại. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```


Trả về slide ghi chú của slide hiện tại. Trả về null nếu slide không có slide ghi chú. Chỉ đọc [INotesSlide](../../com.aspose.slides/inotesslide).

**Trả về:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```


Trả về slide ghi chú của slide hiện tại, tạo mới nếu không tồn tại.

**Trả về:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) cho slide này.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```


Xóa slide ghi chú của slide hiện tại.