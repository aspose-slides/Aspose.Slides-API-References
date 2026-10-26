---
title: NotesSlideManager
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: ノートスライドマネージャー。
type: docs
url: /ja/com.aspose.slides/notesslidemanager/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)  
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

ノートスライドマネージャー。

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // プレゼンテーションファイルを表す Presentation オブジェクトをインスタンス化します
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // 最初のスライドにノートを追加します
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // プレゼンテーションをディスクに保存します
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // プレゼンテーションファイルを表す Presentation オブジェクトをインスタンス化します
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // 最初のスライドのノートを削除します
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // プレゼンテーションをディスクに保存します
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | 現在のスライドのノートスライドを返します。 |
| [addNotesSlide()](#addNotesSlide--) | 現在のスライドのノートスライドを返します。存在しない場合は作成します。 |
| [removeNotesSlide()](#removeNotesSlide--) | 現在のスライドのノートスライドを削除します。 |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```

現在のスライドのノートスライドを返します。スライドにノートスライドがない場合はnullを返します。読み取り専用 [INotesSlide](../../com.aspose.slides/inotesslide)。

**戻り値:**  
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```

現在のスライドのノートスライドを返します。存在しない場合は作成します。

**戻り値:**  
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) このスライド用。
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```

現在のスライドのノートスライドを削除します。