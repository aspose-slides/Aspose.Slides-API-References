---
title: NotesSlideManager
second_title: Aspose.Slides for Java API 參考
description: 備註投影片管理員。
type: docs
url: /zh-hant/com.aspose.slides/notesslidemanager/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面：**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

備註投影片管理員。

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // 實例化一個表示簡報檔案的 Presentation 物件
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // 為第一張投影片新增備註
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // 將簡報儲存至磁碟
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // 實例化一個表示簡報檔案的 Presentation 物件
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // 移除第一張投影片的備註
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // 將簡報儲存至磁碟
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```
## 方法

| 方法 | 說明 |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | 傳回目前投影片的備註投影片。 |
| [addNotesSlide()](#addNotesSlide--) | 傳回目前投影片的備註投影片，若不存在則建立。 |
| [removeNotesSlide()](#removeNotesSlide--) | 移除目前投影片的備註投影片。 |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```

傳回目前投影片的備註投影片。若投影片沒有備註投影片則傳回 null。唯讀 [INotesSlide](../../com.aspose.slides/inotesslide)。

**傳回：**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```

傳回目前投影片的備註投影片，若不存在則建立。

**傳回：**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) for this slide.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```

移除目前投影片的備註投影片。