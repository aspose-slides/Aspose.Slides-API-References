---
title: TextFrame
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili sebuah TextFrame.
type: docs
url: /id/com.aspose.slides/textframe/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject
```
public final class TextFrame implements ITextFrame, IDOMObject
```

Mewakili sebuah TextFrame.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | Mengembalikan daftar semua paragraf dalam sebuah frame. |
| [getText()](#getText--) | Mendapatkan atau mengatur teks biasa untuk TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Mendapatkan atau mengatur teks biasa untuk TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Mengembalikan objek pemformatan untuk objek TextFrame ini. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Memberikan akses mudah ke hyperlink yang terkandung. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Menggabungkan run dengan pemformatan yang sama di semua paragraf. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Menyorot semua kecocokan teks contoh dengan warna yang ditentukan. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Menyorot semua kecocokan teks contoh dengan warna yang ditentukan. |
| [splitTextByColumns()](#splitTextByColumns--) | Membagi konten teks dari [ITextFrame](../../com.aspose.slides/itextframe) menjadi array string, di mana setiap elemen sesuai dengan kolom teks terpisah di dalam frame. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Menyorot semua kecocokan teks contoh dengan warna yang ditentukan. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Menyorot semua kecocokan regular expression dengan warna yang ditentukan. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Menyorot semua kecocokan regular expression dengan warna yang ditentukan. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Mengganti semua kemunculan teks yang ditentukan dengan teks lain yang ditentukan. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Mengganti semua kecocokan regular expression dengan string yang ditentukan. |
| [getSlide()](#getSlide--) | Mengembalikan slide induk dari TextFrame. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk dari TextFrame. |
| [getParentShape()](#getParentShape--) | Mengembalikan shape induk atau null jika objek induk tidak mengimplementasikan antarmuka IShape. Hanya-baca [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Mengembalikan sel induk atau null jika objek induk tidak mengimplementasikan antarmuka ICell. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject
### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

Mengembalikan daftar semua paragraf dalam sebuah frame. Hanya-baca [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Mengembalikan:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public final String getText()
```

Mendapatkan atau mengatur teks biasa untuk TextFrame. Baca/tulis String.

Nilai: Teks.

**Mengembalikan:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Mendapatkan atau mengatur teks biasa untuk TextFrame. Baca/tulis String.

Nilai: Teks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

Mengembalikan objek pemformatan untuk objek TextFrame ini. Hanya-baca [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Mengembalikan:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Memberikan akses mudah ke hyperlink yang terkandung. Hanya-baca [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Mengembalikan:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Menggabungkan run dengan pemformatan yang sama di semua paragraf.
### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

Menyorot semua kecocokan teks contoh dengan warna yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Contoh teks untuk disorot. |
| highlightColor | java.lang.Integer | Warna untuk menyorot teks. |
### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

Menyorot semua kecocokan teks contoh dengan warna yang ditentukan.

--------------------

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // menyorot semua kata 'important'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // menyorot semua kemunculan terpisah 'the'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("to", Color.MAGENTA, textHighlightingOptions);
>      pres.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan disorot. |
| highlightColor | java.lang.Integer | Warna untuk menyorot teks. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Opsi penyorotan. |
### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

Membagi konten teks dari [ITextFrame](../../com.aspose.slides/itextframe) menjadi array string, di mana setiap elemen sesuai dengan kolom teks terpisah di dalam frame.

--------------------

> ```
> Contoh berikut menunjukkan cara menggunakan #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Dapatkan shape pertama pada slide dan cast ke ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Bagi konten text frame menjadi kolom
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Cetak teks setiap kolom ke konsol
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
java.lang.String[] - Sebuah array string, di mana setiap string mewakili konten teks dari kolom tertentu di [ITextFrame](../../com.aspose.slides/itextframe).

--------------------

Jika TextFrame tidak berisi beberapa kolom, array yang dikembalikan akan memiliki satu elemen yang berisi teks lengkap. Kolom kosong akan direpresentasikan sebagai string kosong dalam array.
### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Menyorot semua kecocokan teks contoh dengan warna yang ditentukan.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // menyorot semua kata 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // menyorot semua kemunculan terpisah 'the'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan disorot. |
| highlightColor | java.lang.Integer | Warna untuk menyorot teks. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opsi pencarian teks [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objek callback untuk menerima hasil pencarian [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

Menyorot semua kecocokan regular expression dengan warna yang ditentukan.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // menyorot semua kata dengan 10 simbol atau lebih
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| regex | java.lang.String | Teks regular expression untuk mendapatkan teks yang akan disorot. |
| highlightColor | java.lang.Integer | Warna untuk menyorot teks. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Opsi penyorotan. |
### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Menyorot semua kecocokan regular expression dengan warna yang ditentukan.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // menyorot semua kata dengan 5 simbol atau lebih
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Regular expression java.util.regex.Pattern untuk mendapatkan string yang akan disorot. |
| highlightColor | java.lang.Integer | Warna untuk menyorot teks. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objek callback untuk menerima hasil pencarian [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Mengganti semua kemunculan teks yang ditentukan dengan teks lain yang ditentukan.

--------------------

> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Ganti semua kemunculan terpisah 'the' dengan '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| oldText | java.lang.String | String yang akan diganti. |
| newText | java.lang.String | String untuk mengganti semua kemunculan oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opsi pencarian teks [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objek callback untuk menyimpan hasil operasi penggantian [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Mengganti semua kecocokan regular expression dengan string yang ditentukan.

--------------------

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Ganti semua kata dengan 5 simbol atau lebih dengan '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Regular expression java.util.regex.Pattern untuk mendapatkan string yang akan diganti. |
| newText | java.lang.String | String untuk mengganti semua kemunculan string yang akan diganti. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objek callback untuk menyimpan hasil operasi penggantian [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Mengembalikan slide induk dari TextFrame. Hanya-baca [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan presentasi induk dari TextFrame. Hanya-baca [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

Mengembalikan shape induk atau null jika objek induk tidak mengimplementasikan antarmuka IShape. Hanya-baca [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Asersi ini selalu benar
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape)
### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```

Mengembalikan sel induk atau null jika objek induk tidak mengimplementasikan antarmuka ICell. Hanya-baca [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Asersi ini selalu benar
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Mengembalikan:**
[ICell](../../com.aspose.slides/icell)