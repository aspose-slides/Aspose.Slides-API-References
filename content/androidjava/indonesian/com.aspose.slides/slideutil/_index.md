---
title: SlideUtil
second_title: Referensi API Java Aspose.Slides untuk Android
description: Menyediakan metode yang membantu mencari bentuk dan teks dalam presentasi.
type: docs
url: /id/com.aspose.slides/slideutil/
---
**Inheritance:**
java.lang.Object
```
public class SlideUtil
```

Menyediakan metode yang membantu mencari bentuk dan teks dalam presentasi.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | Temukan bentuk berdasarkan teks alternatif dalam presentasi PPTX. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | Temukan bentuk berdasarkan teks alternatif pada slide dalam presentasi PPTX. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | Mencari semua bentuk pada slide yang ditentukan yang cocok dengan jenis placeholder yang diberikan. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | Mengubah penempatan semua bentuk pada slide. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | Mengubah penempatan bentuk terpilih pada slide. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | Mengubah penempatan semua bentuk dalam grup bentuk. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | Mengubah penempatan bentuk terpilih dalam grup bentuk. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | Menemukan dan mengganti teks dalam presentasi dengan format yang diberikan |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | Menemukan dan mengganti teks dalam presentasi dengan format yang diberikan |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Mengembalikan semua bingkai teks pada slide dalam presentasi PPTX. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | Mengembalikan semua bingkai teks pada slide yang ditentukan yang berisi teks yang diberikan. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Mengembalikan semua bingkai teks dalam presentasi PPTX. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | Mengonversi format file sumber ke [SaveFormat](../../com.aspose.slides/saveformat) yang sesuai. |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```


### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```


Temukan bentuk berdasarkan teks alternatif dalam presentasi PPTX.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Presentasi yang dipindai. |
| altText | java.lang.String | Teks alternatif dari sebuah bentuk. |

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape) - Shape atau null.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```


Temukan bentuk berdasarkan teks alternatif pada slide dalam presentasi PPTX.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide yang dipindai. |
| altText | java.lang.String | Teks alternatif dari sebuah bentuk. |

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape) - Shape atau null.
### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```


Mencari semua bentuk pada slide yang ditentukan yang cocok dengan jenis placeholder yang diberikan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide untuk mencari bentuk. |
| placeholderType | byte | Jenis placeholder untuk memfilter bentuk. |

**Mengembalikan:**
com.aspose.slides.IShape[] - Array dari objek [IShape](../../com.aspose.slides/ishape) yang cocok dengan jenis placeholder yang ditentukan.
### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```


Mengubah penempatan semua bentuk pada slide. Menyelaraskan bentuk ke margin atau tepi slide atau menyelaraskannya relatif satu sama lain.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, true, pres.getSlides().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alignmentType | int | Menentukan jenis penyelarasan yang akan diterapkan. |
| alignToSlide | boolean | Jika true, bentuk akan diselaraskan relatif terhadap tepi slide. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide induk. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```


Mengubah penempatan bentuk terpilih pada slide. Menyelaraskan bentuk ke margin atau tepi slide atau menyelaraskannya relatif satu sama lain.

--------------------

> ```
> Example:
>   
>   Presentation pres = new Presentation("pres.pptx");
>   try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape1 = slide.getShapes().get_Item(0);
>      IShape shape2 = slide.getShapes().get_Item(1);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, false, pres.getSlides().get_Item(0), new int[]
>      {
>          slide.getShapes().indexOf(shape1),
>          slide.getShapes().indexOf(shape2)
>      });
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alignmentType | int | Menentukan jenis penyelarasan yang akan diterapkan. |
| alignToSlide | boolean | Jika true, bentuk akan diselaraskan relatif terhadap tepi slide. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide induk. |
| shapeIndexes | int[] | Indeks bentuk yang akan diselaraskan. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```


Mengubah penempatan semua bentuk dalam grup bentuk. Menyelaraskan bentuk ke margin atau tepi slide atau menyelaraskannya relatif satu sama lain.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape) slide.getShapes().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alignmentType | int | Menentukan jenis penyelarasan yang akan diterapkan. |
| alignToSlide | boolean | Jika true, bentuk akan diselaraskan relatif terhadap tepi slide. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Grup bentuk induk. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```


Mengubah penempatan bentuk terpilih dalam grup bentuk. Menyelaraskan bentuk ke margin atau tepi slide atau menyelaraskannya relatif satu sama lain.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.getShapes().get_Item(0), new int[] { 0, 2 });
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alignmentType | int | Menentukan jenis penyelarasan yang akan diterapkan. |
| alignToSlide | boolean | Jika true, bentuk akan diselaraskan relatif terhadap tepi slide. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Grup bentuk induk. |
| shapeIndexes | int[] | Indeks bentuk yang akan diselaraskan. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```


Menemukan dan mengganti teks dalam presentasi dengan format yang diberikan

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentasi yang dipindai. |
| withMasters | boolean | Menentukan apakah slide master harus dipindai. |
| find | java.lang.String | Nilai string yang akan dicari. |
| replace | java.lang.String | Nilai string untuk mengganti. Karakter dari string yang ditemukan |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```


Menemukan dan mengganti teks dalam presentasi dengan format yang diberikan

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentasi yang dipindai. |
| withMasters | boolean | Menentukan apakah slide master harus dipindai. |
| find | java.lang.String | Nilai string yang akan dicari. |
| replace | java.lang.String | Nilai string untuk mengganti. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | Format untuk mengganti bagian teks. Jika null, maka format dari karakter pertama dari string yang ditemukan akan digunakan |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```


Mengembalikan semua bingkai teks pada slide dalam presentasi PPTX.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide yang dipindai. |

**Mengembalikan:**
com.aspose.slides.ITextFrame[] - Array dari objek [TextFrame](../../com.aspose.slides/textframe).
### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```


Mengembalikan semua bingkai teks pada slide yang ditentukan yang berisi teks yang diberikan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide untuk pencarian. |
| text | java.lang.String | Teks yang akan dicari dalam bingkai teks. |
| checkPlaceholderText | boolean | Menunjukkan apakah termasuk bingkai teks yang kosong, tetapi teks placeholder-nya mengandung teks pencarian. |

**Mengembalikan:**
com.aspose.slides.ITextFrame[] - Array dari objek [ITextFrame](../../com.aspose.slides/itextframe) yang berisi teks yang ditentukan.
### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```


Mengembalikan semua bingkai teks dalam presentasi PPTX.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Presentasi yang dipindai. |
| withMasters | boolean | Menentukan apakah slide master harus dipindai. |

**Mengembalikan:**
com.aspose.slides.ITextFrame[] - Array dari objek [TextFrame](../../com.aspose.slides/textframe).
### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```


Mengonversi format file sumber ke [SaveFormat](../../com.aspose.slides/saveformat) yang sesuai.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | int | Format file sumber. |

**Mengembalikan:**
int - Nilai [SaveFormat](../../com.aspose.slides/saveformat) yang sesuai.