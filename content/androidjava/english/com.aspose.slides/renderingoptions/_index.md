---
title: RenderingOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Provides options that control how a presentation/slide is rendered.
type: docs
url: /com.aspose.slides/renderingoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.IRenderingOptions](../../com.aspose.slides/irenderingoptions)
```
public class RenderingOptions extends SaveOptions implements IRenderingOptions
```

Provides options that control how a presentation/slide is rendered.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      IRenderingOptions renderingOpts = new RenderingOptions();
>      renderingOpts.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomTruncated);
>      FileOutputStream out = new FileOutputStream("pres-Original.png");
>      pres.getSlides().get_Item(0).getThumbnail(renderingOpts).compress(android.graphics.Bitmap.CompressFormat.JPEG, 100, out);
>      out.flush();
>      out.close();
>      renderingOpts.setDefaultRegularFont("Arial Black");
>      FileOutputStream out = new FileOutputStream("pres-ArialBlackDefault.png");
>      pres.getSlides().get_Item(0).getThumbnail(renderingOpts).compress(android.graphics.Bitmap.CompressFormat.JPEG, 100, out);
>      out.flush();
>      out.close();
>      renderingOpts.setDefaultRegularFont("Arial Narrow");
>      FileOutputStream out = new FileOutputStream("pres-ArialNarrowDefault.png");
>      pres.getSlides().get_Item(0).getThumbnail(renderingOpts).compress(android.graphics.Bitmap.CompressFormat.JPEG, 100, out);
>      out.flush();
>      out.close();
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [RenderingOptions()](#RenderingOptions--) | Default constructor. |
## Methods

| Method | Description |
| --- | --- |
| [getNotesCommentsLayouting()](#getNotesCommentsLayouting--) | Provides options that control how notes and comments is placed in exported document. |
### RenderingOptions() {#RenderingOptions--}
```
public RenderingOptions()
```


Default constructor.

### getNotesCommentsLayouting() {#getNotesCommentsLayouting--}
```
public final INotesCommentsLayoutingOptions getNotesCommentsLayouting()
```


Provides options that control how notes and comments is placed in exported document.

**Returns:**
[INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions)
