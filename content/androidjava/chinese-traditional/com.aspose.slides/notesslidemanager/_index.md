---
title: NotesSlideManager
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 備註投影片管理器。
type: docs
url: /zh-hant/com.aspose.slides/notesslidemanager/
---
**繼承:**
java.lang.Object, com.aspose.slides.DomObject

**已實作的所有介面:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

備註投影片管理器。

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // 實例化一個代表簡報檔案的 Presentation 物件
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // 為第一張投影片新增備註
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // 將簡報儲存到磁碟
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // 實例化一個代表簡報檔案的 Presentation 物件
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // 移除第一張投影片的備註
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // 將簡報儲存到磁碟
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 方法

| 方法 | 說明 |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | 返回當前投影片的備註投影片。 |
| [addNotesSlide()](#addNotesSlide--) | 返回當前投影片的備註投影片，如果不存在則會建立。 |
| [removeNotesSlide()](#removeNotesSlide--) | 移除當前投影片的備註投影片。 |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```

返回當前投影片的備註投影片。如果投影片沒有備註投影片，則返回 null。唯讀 [INotesSlide](../../com.aspose.slides/inotesslide)。

**返回:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```

返回當前投影片的備註投影片，如果不存在則會建立。

**返回:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) 針對此投影片。
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```

移除當前投影片的備註投影片。