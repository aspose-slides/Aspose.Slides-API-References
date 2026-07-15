---
title: Output
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một tập hợp các phần tử đầu ra cho IWebDocument.
type: docs
url: /vi/com.aspose.slides/output/
---
**Kế thừa:**
java.lang.Object
```
public final class Output
```

Biểu diễn một tập hợp các phần tử đầu ra cho IWebDocument.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Thêm một phần tử đầu ra cho đối tượng ngữ cảnh. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Thêm một phần tử đầu ra cho hình ảnh. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Thêm một phần tử đầu ra cho hình ảnh. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Thêm một phần tử đầu ra cho video. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Tạo và thêm một phần tử tệp đầu ra cho phông chữ được chỉ định. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Thêm một phần tử đầu ra cho nội dung văn bản. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Liên kết tài nguyên với tệp đầu ra. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Trả về đường dẫn cho một tài nguyên cho trước. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```


Thêm một phần tử đầu ra cho đối tượng ngữ cảnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| path | java.lang.String | Đường dẫn đầu ra. |
| templateKey | java.lang.String | Khóa của mẫu được sử dụng để chuyển đổi đối tượng ngữ cảnh trước khi xuất. |
| contextObject | TContextObject | Đối tượng ngữ cảnh. |

**Trả về:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) đối tượng cho đối tượng ngữ cảnh.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```


Thêm một phần tử đầu ra cho hình ảnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| path | java.lang.String | Đường dẫn đầu ra. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Hình ảnh để xuất. |

**Trả về:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) đối tượng cho hình ảnh.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```


Thêm một phần tử đầu ra cho hình ảnh.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| path | java.lang.String | Đường dẫn đầu ra. |
| image | [IImage](../../com.aspose.slides/iimage) | Hình ảnh để xuất. |

**Trả về:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) đối tượng cho hình ảnh.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```


Thêm một phần tử đầu ra cho video.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| path | java.lang.String | Đường dẫn đầu ra. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video để xuất. |

**Trả về:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) đối tượng cho video.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```


Tạo và thêm một phần tử tệp đầu ra cho phông chữ được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| path | java.lang.String | Đường dẫn tệp nơi phông chữ sẽ được lưu. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Dữ liệu phông chữ sẽ được ghi vào đầu ra. |
| fontStyle | int | Kiểu phông chữ (ví dụ: Regular, Bold, Italic). |

**Trả về:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - Một [IOutputFile](../../com.aspose.slides/ioutputfile) instance cho phông chữ đã tạo.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```


Thêm một phần tử đầu ra cho nội dung văn bản.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| path | java.lang.String | Đường dẫn đầu ra. |
| textContent | java.lang.String | Nội dung để xuất. |

**Trả về:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) đối tượng cho nội dung văn bản.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```


Liên kết tài nguyên với tệp đầu ra.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Tệp đầu ra. |
| obj | java.lang.Object | Đối tượng tài nguyên. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```


Trả về đường dẫn cho một tài nguyên cho trước.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | Đối tượng tài nguyên. |

**Trả về:**
java.lang.String - Đường dẫn tài nguyên.