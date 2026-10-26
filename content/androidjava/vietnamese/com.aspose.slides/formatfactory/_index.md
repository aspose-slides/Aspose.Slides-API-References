---
title: FormatFactory
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cho phép tạo định dạng qua giao diện COM.
type: docs
url: /vi/com.aspose.slides/formatfactory/
---
**Kế thừa:**  
java.lang.Object

**Tất cả giao diện đã triển khai:**  
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)  
```
public class FormatFactory implements IFormatFactory
```

Cho phép tạo định dạng qua giao diện COM.
## Các hàm khởi tạo

| Constructor | Description |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## Các phương thức

| Method | Description |
| --- | --- |
| [getInstance()](#getInstance--) | Format factory static instance. |
| [createPortionFormat()](#createPortionFormat--) | Creates new [IPortionFormat](../../com.aspose.slides/iportionformat). |
| [createParagraphFormat()](#createParagraphFormat--) | Creates new [IParagraphFormat](../../com.aspose.slides/iparagraphformat). |
| [createTextFrameFormat()](#createTextFrameFormat--) | Creates new [ITextFrameFormat](../../com.aspose.slides/itextframeformat). |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```

### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```

Format factory static instance. Chỉ đọc [FormatFactory](../../com.aspose.slides/formatfactory).

**Trả về:**  
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```

Tạo mới [IPortionFormat](../../com.aspose.slides/iportionformat).

**Trả về:**  
[IPortionFormat](../../com.aspose.slides/iportionformat) - New portion format.
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```

Tạo mới [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Trả về:**  
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - New paragraph format.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```

Tạo mới [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Trả về:**  
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - New text frame format.