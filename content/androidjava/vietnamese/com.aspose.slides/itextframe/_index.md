---
title: ITextFrame
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một TextFrame.
type: docs
url: /vi/com.aspose.slides/itextframe/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

Đại diện cho một TextFrame.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | Trả về danh sách tất cả các đoạn văn trong khung. |
| [getText()](#getText--) | Lấy hoặc đặt văn bản thuần cho một TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Lấy hoặc đặt văn bản thuần cho một TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Trả về đối tượng định dạng cho đối tượng TextFrame này. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Cung cấp truy cập dễ dàng đến các siêu liên kết được chứa. |
| [getParentShape()](#getParentShape--) | Trả về hình dạng cha hoặc null nếu đối tượng cha không triển khai giao diện IShape. Chỉ đọc [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Trả về ô cha hoặc null nếu đối tượng cha không triển khai giao diện ICell. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Nối các phần chạy có cùng định dạng trong tất cả các đoạn văn. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Tô sáng tất cả các khớp của văn bản mẫu với màu đã chỉ định. |
| [splitTextByColumns()](#splitTextByColumns--) | Tách nội dung văn bản của [ITextFrame](../../com.aspose.slides/itextframe) thành một mảng các chuỗi, mỗi phần tử tương ứng với một cột văn bản riêng biệt trong khung. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Tô sáng tất cả các khớp của văn bản mẫu với màu đã chỉ định. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Tô sáng tất cả các khớp của văn bản mẫu với màu đã chỉ định. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Tô sáng tất cả các khớp của biểu thức chính quy với màu đã chỉ định. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Tô sáng tất cả các khớp của biểu thức chính quy với màu đã chỉ định. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Thay thế mọi lần xuất hiện của văn bản đã chỉ định bằng một văn bản khác đã chỉ định. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Thay thế tất cả các khớp của biểu thức chính quy bằng chuỗi đã chỉ định. |
### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```


Trả về danh sách tất cả các đoạn văn trong khung. Chỉ đọc [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Giá trị trả về:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public abstract String getText()
```


Lấy hoặc đặt văn bản thuần cho một TextFrame. Đọc/ghi String.

Giá trị: Văn bản.

**Giá trị trả về:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Lấy hoặc đặt văn bản thuần cho một TextFrame. Đọc/ghi String.

Giá trị: Văn bản.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```


Trả về đối tượng định dạng cho đối tượng TextFrame này. Chỉ đọc [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Giá trị trả về:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```


Cung cấp truy cập dễ dàng đến các siêu liên kết được chứa. Chỉ đọc [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Giá trị trả về:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```


Trả về hình dạng cha hoặc null nếu đối tượng cha không triển khai giao diện IShape. Chỉ đọc [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Các khẳng định này luôn đúng
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
public abstract ICell getParentCell()
```


Trả về ô cha hoặc null nếu đối tượng cha không triển khai giao diện ICell. Chỉ đọc [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Các khẳng định này luôn đúng
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Giá trị trả về:**
[ICell](../../com.aspose.slides/icell)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Nối các phần chạy có cùng định dạng trong tất cả các đoạn văn.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```


Tô sáng tất cả các khớp của văn bản mẫu với màu đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần tô sáng. |
| highlightColor | java.lang.Integer | Màu để tô sáng văn bản. |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```


Tách nội dung văn bản của [ITextFrame](../../com.aspose.slides/itextframe) thành một mảng các chuỗi, mỗi phần tử tương ứng với một cột văn bản riêng biệt trong khung.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Lấy hình dạng đầu tiên trên slide và chuyển đổi nó sang ITextFrame
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
java.lang.String[] - Một mảng các chuỗi, trong đó mỗi chuỗi đại diện cho nội dung văn bản của một cột cụ thể trong [ITextFrame](../../com.aspose.slides/itextframe).

--------------------

Nếu khung văn bản không chứa nhiều cột, mảng trả về sẽ có một phần tử duy nhất chứa toàn bộ văn bản. Các cột trống sẽ được biểu diễn dưới dạng chuỗi rỗng trong mảng.
### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```


Tô sáng tất cả các khớp của văn bản mẫu với màu đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản cần tô sáng. |
| highlightColor | java.lang.Integer | Màu để tô sáng văn bản. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Các tùy chọn tô sáng. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


Tô sáng tất cả các khớp của văn bản mẫu với màu đã chỉ định.

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
>      // tô sáng tất cả các lần xuất hiện riêng biệt của 'the'
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
| highlightColor | java.lang.Integer | Màu để tô sáng văn bản. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Các tùy chọn tìm kiếm văn bản [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Đối tượng callback để nhận kết quả tìm kiếm [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```


Tô sáng tất cả các khớp của biểu thức chính quy với màu đã chỉ định.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // tô sáng tất cả các từ có 5 ký tự hoặc dài hơn
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
| highlightColor | java.lang.Integer | Màu để tô sáng văn bản. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Đối tượng callback để nhận kết quả tìm kiếm [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```


Tô sáng tất cả các khớp của biểu thức chính quy với màu đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| regex | java.lang.String | Văn bản của biểu thức chính quy để lấy văn bản cần tô sáng. |
| highlightColor | java.lang.Integer | Màu để tô sáng văn bản. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Các tùy chọn tô sáng. |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```


Thay thế mọi lần xuất hiện của văn bản đã chỉ định bằng một văn bản khác đã chỉ định.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
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
| newText | java.lang.String | Chuỗi để thay thế mọi lần xuất hiện của oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Các tùy chọn tìm kiếm văn bản [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Đối tượng callback để nhận kết quả tìm kiếm [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


Thay thế tất cả các khớp của biểu thức chính quy bằng chuỗi đã chỉ định.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Thay thế tất cả các từ có 5 ký tự hoặc dài hơn bằng '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Biểu thức chính quy java.util.regex.Pattern để lấy các chuỗi cần thay thế. |
| newText | java.lang.String | Chuỗi để thay thế mọi lần xuất hiện của chuỗi cần được thay thế. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Đối tượng callback để nhận kết quả tìm kiếm [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
