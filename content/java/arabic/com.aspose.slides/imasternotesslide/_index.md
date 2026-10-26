---
title: IMasterNotesSlide
second_title: Aspose.Slides لـ Java مرجع API
description: يمثل الشريحة الرئيسية للملاحظات.
type: docs
url: /ar/com.aspose.slides/imasternotesslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

يمثل الشريحة الرئيسية للملاحظات.

## الطرق

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | يُعيد مدير HeaderFooter لشريحة الملاحظات الرئيسية. |
| [getNotesStyle()](#getNotesStyle--) | يُعيد نمط نص الملاحظات. |
| [getDrawingGuides()](#getDrawingGuides--) | يُعيد مجموعة من إرشادات الرسم لشريحة الملاحظات الرئيسية. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

يُعيد مدير HeaderFooter لشريحة الملاحظات الرئيسية. للقراءة فقط [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager).

**الإرجاع:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)

### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```

يُعيد نمط نص الملاحظات. للقراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**الإرجاع:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

يُعيد مجموعة من إرشادات الرسم لشريحة الملاحظات الرئيسية. للقراءة فقط [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // إضافة دليل الرسم الأفقي الجديد أسفل مركز الشريحة
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)