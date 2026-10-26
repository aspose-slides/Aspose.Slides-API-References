---
title: FormatFactory
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cho phép tạo định dạng qua giao diện COM.
type: docs
url: /vi/com.aspose.slides/formatfactory/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

Cho phép tạo định dạng qua giao diện COM.
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getInstance()](#getInstance--) | Đối tượng tĩnh của nhà máy định dạng. |
| [createPortionFormat()](#createPortionFormat--) | Tạo mới [IPortionFormat](../../com.aspose.slides/iportionformat). |
| [createParagraphFormat()](#createParagraphFormat--) | Tạo mới [IParagraphFormat](../../com.aspose.slides/iparagraphformat). |
| [createTextFrameFormat()](#createTextFrameFormat--) | Tạo mới [ITextFrameFormat](../../com.aspose.slides/itextframeformat). |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```


### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```


Đối tượng tĩnh của nhà máy định dạng. Chỉ đọc [FormatFactory](../../com.aspose.slides/formatfactory).

**Trả về:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```


Tạo mới [IPortionFormat](../../com.aspose.slides/iportionformat).

**Trả về:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - Định dạng đoạn mới.
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```


Tạo mới [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Trả về:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Định dạng đoạn văn mới.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```


Tạo mới [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Trả về:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - Định dạng khung văn bản mới.