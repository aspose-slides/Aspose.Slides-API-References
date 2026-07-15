---
title: Merger
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một nhóm các phương thức để hợp nhất các bản trình chiếu PowerPoint có cùng định dạng thành một tệp tin.
type: docs
url: /vi/com.aspose.slides/merger/
---
**Kế thừa:**
java.lang.Object
```
public class Merger
```

Đại diện cho một nhóm các phương thức để hợp nhất các bản trình chiếu PowerPoint có cùng định dạng thành một tệp tin.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | Merges multiple PowerPoint presentations of the same format into a single presentation file. |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```

Kết hợp nhiều bản thuyết trình PowerPoint có cùng định dạng thành một tệp bản thuyết trình duy nhất.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Một mảng các tên tệp bản trình chiếu đầu vào. |
| outputFileName | java.lang.String | Tên tệp đầu ra của tệp bản trình chiếu đã hợp nhất. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```

Kết hợp nhiều bản thuyết trình PowerPoint có cùng định dạng thành một tệp bản thuyết trình duy nhất.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Một mảng các tên tệp bản trình chiếu đầu vào. |
| outputFileName | java.lang.String | Tên tệp đầu ra của tệp bản trình chiếu đã hợp nhất. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Các tùy chọn bổ sung xác định cách lưu bản trình chiếu đã hợp nhất. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```

Kết hợp nhiều bản thuyết trình PowerPoint có cùng định dạng thành một tệp bản thuyết trình duy nhất.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Một mảng các tên tệp bản trình chiếu đầu vào. |
| outputStream | java.io.OutputStream | Luồng đầu ra. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```

Kết hợp nhiều bản thuyết trình PowerPoint có cùng định dạng thành một tệp bản thuyết trình duy nhất.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | Một mảng các tên tệp bản trình chiếu đầu vào. |
| outputStream | java.io.OutputStream | Luồng đầu ra. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Các tùy chọn bổ sung xác định cách lưu bản trình chiếu đã hợp nhất. |