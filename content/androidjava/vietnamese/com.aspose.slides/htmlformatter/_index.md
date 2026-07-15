---
title: HtmlFormatter
second_title: Tham chiếu API Java cho Aspose.Slides cho Android
description: Đại diện cho mẫu tệp HTML.
type: docs
url: /vi/com.aspose.slides/htmlformatter/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

Đại diện cho mẫu tệp HTML.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Creates and returns HTML formatter for a simple document view which consists of sequences of slides one below another. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Creates and returns HTML formatter for a simple slide show html which shows slides one after another. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Creates and returns HTML formatter for custom callback-driven html generation. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

Tạo và trả về bộ định dạng HTML cho một chế độ xem tài liệu đơn giản, bao gồm các slide xếp chồng lên nhau.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| css | java.lang.String | Chỉ định CSS cho tệp này. |
| showSlideTitle | boolean | Thêm tiêu đề slide nếu có tiêu đề phía trên hình ảnh slide. |

**Giá trị trả về:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Đối tượng [HtmlFormatter](../../com.aspose.slides/htmlformatter).
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

Tạo và trả về bộ định dạng HTML cho một trình chiếu slide đơn giản hiển thị các slide liên tiếp nhau.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| css | java.lang.String | Chỉ định URL của tệp CCS được sử dụng. |
| showSlideTitle | boolean | Thêm tiêu đề slide nếu có tiêu đề phía trên hình ảnh slide. |

**Giá trị trả về:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Đối tượng [HtmlFormatter](../../com.aspose.slides/htmlformatter).
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

Tạo và trả về bộ định dạng HTML cho việc tạo HTML dựa trên callback tùy chỉnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Giao diện callback kiểm soát việc tạo tệp html. |

**Giá trị trả về:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Đối tượng [HtmlFormatter](../../com.aspose.slides/htmlformatter).