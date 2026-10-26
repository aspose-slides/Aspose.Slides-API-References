---
title: NotesSlideManager
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Trình quản lý slide ghi chú.
type: docs
url: /vi/com.aspose.slides/notesslidemanager/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả giao diện được thực hiện:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

Trình quản lý slide ghi chú.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // Khởi tạo đối tượng Presentation đại diện cho một tệp trình chiếu
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Thêm ghi chú vào slide đầu tiên
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // Lưu trình chiếu vào đĩa
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // Khởi tạo đối tượng Presentation đại diện cho một tệp trình chiếu
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // Xóa ghi chú của slide đầu tiên
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // Lưu trình chiếu vào đĩa
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Phương thức

| Method | Description |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | Trả về slide ghi chú cho slide hiện tại. |
| [addNotesSlide()](#addNotesSlide--) | Trả về slide ghi chú cho slide hiện tại, tạo mới nếu không tồn tại. |
| [removeNotesSlide()](#removeNotesSlide--) | Xóa slide ghi chú của slide hiện tại. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```


Trả về slide ghi chú cho slide hiện tại. Trả về null nếu slide không có slide ghi chú. Chỉ đọc [INotesSlide](../../com.aspose.slides/inotesslide).

**Trả về:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```


Trả về slide ghi chú cho slide hiện tại, tạo mới nếu không tồn tại.

**Trả về:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) cho slide này.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```


Xóa slide ghi chú của slide hiện tại.