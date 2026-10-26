---
title: TextFrame
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một TextFrame.
type: docs
url: /vi/com.aspose.slides/textframe/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject
```
public final class TextFrame implements ITextFrame, IDOMObject
```

Biểu diễn một TextFrame.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | Trả về danh sách tất cả các đoạn văn trong một khung. |
| [getText()](#getText--) | Lấy hoặc đặt văn bản thuần cho một TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Lấy hoặc đặt văn bản thuần cho một TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Trả về đối tượng định dạng cho đối tượng TextFrame này. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Cung cấp truy cập dễ dàng tới các siêu liên kết chứa trong. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Ghép các run có cùng định dạng trong tất cả các đoạn văn. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Tô sáng tất cả các khớp của văn bản mẫu bằng màu được chỉ định. |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Tô sáng tất cả các khớp của văn bản mẫu bằng màu được chỉ định. |
| [splitTextByColumns()](#splitTextByColumns--) | Tách nội dung văn bản của [ITextFrame](../../com.aspose.slides/itextframe) thành một mảng các chuỗi, mỗi phần tử tương ứng với một cột văn bản riêng trong khung. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Tô sáng tất cả các khớp của văn bản mẫu bằng màu được chỉ định. |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Tô sáng tất cả các khớp của biểu thức chính quy bằng màu được chỉ định. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Tô sáng tất cả các khớp của biểu thức chính quy bằng màu được chỉ định. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Thay thế tất cả các lần xuất hiện của văn bản được chỉ định bằng một văn bản khác được chỉ định. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Thay thế tất cả các khớp của biểu thức chính quy bằng chuỗi được chỉ định. |
| [getSlide()](#getSlide--) | Trả về slide cha của một TextFrame. |
| [getPresentation()](#getPresentation--) | Trả về bản trình bày cha của một TextFrame. |
| [getParentShape()](#getParentShape--) | Trả về shape cha hoặc null nếu đối tượng cha không thực thi giao diện IShape. Chỉ đọc [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Trả về cell cha hoặc null nếu đối tượng cha không thực thi giao diện ICell. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Giá trị trả về:**
com.aspose.slides.IDOMObject
### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```


Trả về danh sách tất cả các đoạn văn trong một khung. Chỉ đọc [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Giá trị trả về:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public final String getText()
```


Lấy hoặc đặt văn bản thuần cho một TextFrame. Đọc/ghi String.

Giá trị: Văn bản.

**Giá trị trả về:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Lấy hoặc đặt văn bản thuần cho một TextFrame. Đọc/ghi String.

Giá trị: Văn bản.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```


Trả về đối tượng định dạng cho đối tượng TextFrame này. Chỉ đọc [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Giá trị trả về:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```


Cung cấp truy cập dễ dàng tới các siêu liên kết chứa trong. Chỉ đọc [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Giá trị trả về:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Ghép các run có cùng định dạng trong tất cả các đoạn văn.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```


Tô sáng tất cả các khớp của văn bản mẫu bằng màu được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản mẫu để tô sáng. |
| highlightColor | java.awt.Color | Màu để tô sáng văn bản. |

### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```


Tô sáng tất cả các khớp của văn bản mẫu bằng màu được chỉ định.

--------------------

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // tô sáng tất cả các từ 'important'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // tô sáng tất cả các lần xuất hiện riêng lẻ của 'the'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("to", Color.MAGENTA, textHighlightingOptions);
>      pres.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần tô sáng. |
| highlightColor | java.awt.Color | Màu để tô sáng văn bản. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Tùy chọn tô sáng. |

### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```


Tách nội dung văn bản của [ITextFrame](../../com.aspose.slides/itextframe) thành một mảng các chuỗi, mỗi phần tử tương ứng với một cột văn bản riêng trong khung.

--------------------

> ```
> Ví dụ sau đây minh họa cách sử dụng #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Lấy shape đầu tiên trên slide và chuyển đổi sang ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Tách nội dung khung văn bản thành các cột
>      String[] columnsText = textFrame.splitTextByColumns();
>      // In nội dung của mỗi cột ra console
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Giá trị trả về:**
java.lang.String[] - Một mảng các chuỗi, mỗi chuỗi đại diện cho nội dung văn bản của một cột cụ thể trong [ITextFrame](../../com.aspose.slides/itextframe).

--------------------

Nếu khung văn bản không chứa nhiều cột, mảng trả về sẽ chỉ có một phần tử chứa toàn bộ văn bản. Các cột trống sẽ được biểu diễn bằng các chuỗi rỗng trong mảng.
### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


Tô sáng tất cả các khớp của văn bản mẫu bằng màu được chỉ định.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // tô sáng tất cả các từ 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // tô sáng tất cả các lần xuất hiện riêng lẻ của 'the'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần tô sáng. |
| highlightColor | java.awt.Color | Màu để tô sáng văn bản. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Tùy chọn tìm kiếm văn bản [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Đối tượng callback để nhận kết quả tìm kiếm [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```


Tô sáng tất cả các khớp của biểu thức chính quy bằng màu được chỉ định.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // tô sáng tất cả các từ có 10 ký tự trở lên
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| regex | java.lang.String | Văn bản của biểu thức chính quy để lấy văn bản cần tô sáng. |
| highlightColor | java.awt.Color | Màu để tô sáng văn bản. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Tùy chọn tô sáng. |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```


Tô sáng tất cả các khớp của biểu thức chính quy bằng màu được chỉ định.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // tô sáng tất cả các từ có 5 ký tự trở lên
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Biểu thức chính quy java.util.regex.Pattern để lấy các chuỗi cần tô sáng. |
| highlightColor | java.awt.Color | Màu để tô sáng văn bản. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Đối tượng callback để nhận kết quả tìm kiếm [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```


Thay thế tất cả các lần xuất hiện của văn bản được chỉ định bằng một văn bản khác được chỉ định.

--------------------

> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Thay thế tất cả các lần xuất hiện riêng lẻ của 'the' bằng '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| oldText | java.lang.String | Chuỗi cần được thay thế. |
| newText | java.lang.String | Chuỗi thay thế cho tất cả các lần xuất hiện của oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Tùy chọn tìm kiếm văn bản [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Đối tượng callback để lưu kết quả thao tác thay thế [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


Thay thế tất cả các khớp của biểu thức chính quy bằng chuỗi được chỉ định.

--------------------

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Thay thế tất cả các từ có 5 ký tự trở lên bằng '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Biểu thức chính quy java.util.regex.Pattern để lấy các chuỗi cần được thay thế. |
| newText | java.lang.String | Chuỗi thay thế cho tất cả các lần xuất hiện của các chuỗi cần được thay thế. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Đối tượng callback để lưu kết quả thao tác thay thế [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Trả về slide cha của một TextFrame. Chỉ đọc [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Giá trị trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Trả về bản trình bày cha của một TextFrame. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Giá trị trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```


Trả về shape cha hoặc null nếu đối tượng cha không thực thi giao diện IShape. Chỉ đọc [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Những khẳng định này luôn đúng
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Giá trị trả về:**
[IShape](../../com.aspose.slides/ishape)
### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```


Trả về cell cha hoặc null nếu đối tượng cha không thực thi giao diện ICell. Chỉ đọc [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Những khẳng định này luôn đúng
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Giá trị trả về:**
[ICell](../../com.aspose.slides/icell)