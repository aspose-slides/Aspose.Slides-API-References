---
title: TextFrame
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một TextFrame.
type: docs
url: /vi/com.aspose.slides/textframe/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject
```
public final class TextFrame implements ITextFrame, IDOMObject
```

Biểu diễn một TextFrame.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | Trả về danh sách tất cả các đoạn văn trong khung. |
| [getText()](#getText--) | Lấy hoặc đặt văn bản thuần cho một TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Lấy hoặc đặt văn bản thuần cho một TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Trả về đối tượng định dạng cho đối tượng TextFrame này. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Cung cấp quyền truy cập dễ dàng tới các siêu liên kết chứa trong. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Ghép các run có cùng định dạng trong mọi đoạn văn. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Làm nổi bật tất cả các khớp của văn bản mẫu bằng màu được chỉ định. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Làm nổi bật tất cả các khớp của văn bản mẫu bằng màu được chỉ định. |
| [splitTextByColumns()](#splitTextByColumns--) | Phân tách nội dung văn bản của [ITextFrame](../../com.aspose.slides/itextframe) thành một mảng các chuỗi, trong đó mỗi phần tử tương ứng với một cột văn bản riêng biệt trong khung. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Làm nổi bật tất cả các khớp của văn bản mẫu bằng màu được chỉ định. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Làm nổi bật tất cả các khớp của biểu thức chính quy bằng màu được chỉ định. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Làm nổi bật tất cả các khớp của biểu thức chính quy bằng màu được chỉ định. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Thay thế tất cả các lần xuất hiện của văn bản chỉ định bằng một văn bản khác được chỉ định. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Thay thế tất cả các khớp của biểu thức chính quy bằng chuỗi được chỉ định. |
| [getSlide()](#getSlide--) | Trả về slide cha của một TextFrame. |
| [getPresentation()](#getPresentation--) | Trả về bản trình bày cha của một TextFrame. |
| [getParentShape()](#getParentShape--) | Trả về hình dạng cha hoặc null nếu đối tượng cha không triển khai giao diện IShape. Chỉ đọc [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Trả về ô cha hoặc null nếu đối tượng cha không triển khai giao diện ICell. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject

### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

Trả về danh sách tất cả các đoạn văn trong khung. Chỉ đọc [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Trả về:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public final String getText()
```

Lấy hoặc đặt văn bản thuần cho một TextFrame. Đọc/ghi String.

Giá trị: Văn bản.

**Trả về:**
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

**Trả về:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Cung cấp quyền truy cập dễ dàng tới các siêu liên kết chứa trong. Chỉ đọc [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Trả về:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Ghép các run có cùng định dạng trong mọi đoạn văn.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

Làm nổi bật tất cả các khớp của văn bản mẫu bằng màu được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Mẫu văn bản để làm nổi bật. |
| highlightColor | java.lang.Integer | Màu để làm nổi bật văn bản. |

### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

Làm nổi bật tất cả các khớp của văn bản mẫu bằng màu được chỉ định.

--------------------

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // highlighting all words 'important'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // highlighting all separate 'the' occurrences
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("to", Color.MAGENTA, textHighlightingOptions);
>      pres.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần làm nổi bật. |
| highlightColor | java.lang.Integer | Màu để làm nổi bật văn bản. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Tuỳ chọn làm nổi bật. |

### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

Phân tách nội dung văn bản của [ITextFrame](../../com.aspose.slides/itextframe) thành một mảng các chuỗi, trong đó mỗi phần tử tương ứng với một cột văn bản riêng biệt trong khung.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Get the first shape on the slide and cast it to ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Split the text frame content into columns
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Print each column's text to the console
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
java.lang.String[] - Một mảng các chuỗi, trong đó mỗi chuỗi đại diện cho nội dung văn bản của một cột cụ thể trong [ITextFrame](../../com.aspose.slides/itextframe).

Nếu khung văn bản không chứa nhiều cột, mảng trả về sẽ có một phần tử duy nhất chứa toàn bộ văn bản. Các cột trống sẽ được biểu diễn bằng chuỗi rỗng trong mảng.

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Làm nổi bật tất cả các khớp của văn bản mẫu bằng màu được chỉ định.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // làm nổi bật tất cả các từ 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // làm nổi bật tất cả các lần xuất hiện riêng biệt của 'the'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần làm nổi bật. |
| highlightColor | java.lang.Integer | Màu để làm nổi bật văn bản. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Tuỳ chọn tìm kiếm văn bản [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Đối tượng callback để nhận kết quả tìm kiếm [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

Làm nổi bật tất cả các khớp của biểu thức chính quy bằng màu được chỉ định.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // highlighting all words with 10 symbols or longer
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| regex | java.lang.String | Văn bản của biểu thức chính quy để lấy văn bản cần làm nổi bật. |
| highlightColor | java.lang.Integer | Màu để làm nổi bật văn bản. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Tuỳ chọn làm nổi bật. |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Làm nổi bật tất cả các khớp của biểu thức chính quy bằng màu được chỉ định.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // làm nổi bật tất cả các từ có 5 ký tự trở lên
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Biểu thức chính quy java.util.regex.Pattern để lấy các chuỗi cần làm nổi bật. |
| highlightColor | java.lang.Integer | Màu để làm nổi bật văn bản. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Đối tượng callback để nhận kết quả tìm kiếm [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Thay thế tất cả các lần xuất hiện của văn bản chỉ định bằng một văn bản khác được chỉ định.

--------------------

> ```
> Mã mẫu sau đây cho thấy cách thay thế một chuỗi được chỉ định bằng một chuỗi khác được chỉ định.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Thay thế tất cả các lần xuất hiện riêng biệt của 'the' bằng '***'
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
| newText | java.lang.String | Chuỗi để thay thế tất cả các lần xuất hiện của oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Tuỳ chọn tìm kiếm văn bản [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
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
| newText | java.lang.String | Chuỗi để thay thế tất cả các lần xuất hiện của các chuỗi cần được thay thế. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Đối tượng callback để lưu kết quả thao tác thay thế [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Trả về slide cha của một TextFrame. Chỉ đọc [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Trả về bản trình bày cha của một TextFrame. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

Trả về hình dạng cha hoặc null nếu đối tượng cha không triển khai giao diện IShape. Chỉ đọc [IShape](../../com.aspose.slides/ishape).

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

**Trả về:**
[IShape](../../com.aspose.slides/ishape)

### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```

Trả về ô cha hoặc null nếu đối tượng cha không triển khai giao diện ICell. Chỉ đọc [ICell](../../com.aspose.slides/icell).

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


**Trả về:**
[ICell](../../com.aspose.slides/icell)