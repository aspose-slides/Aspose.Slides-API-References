---
title: IAutoShape
second_title: Aspose.Slides cho Java API Reference
description: Biểu diễn một AutoShape.
type: docs
url: /vi/com.aspose.slides/iautoshape/
---
**All Implemented Interfaces:**  
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Biểu diễn một AutoShape.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Trả về các khóa của AutoShape. |
| [getTextFrame()](#getTextFrame--) | Trả về đối tượng TextFrame cho AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Xác định xem autoshape này có nên được tô đầy bằng nền của slide thay vì được chỉ định bằng kiểu dáng hoặc định dạng tô màu hay không. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Xác định xem autoshape này có nên được tô đầy bằng nền của slide thay vì được chỉ định bằng kiểu dáng hoặc định dạng tô màu hay không. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Thêm một TextFrame mới vào một shape. |
| [isTextBox()](#isTextBox--) | Chỉ định nếu shape là một hộp văn bản. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


Trả về các khóa của AutoShape. Chỉ đọc [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Trả về:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Trả về đối tượng TextFrame cho AutoShape. Chỉ đọc [ITextFrame](../../com.aspose.slides/itextframe).

**Trả về:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


Xác định xem autoshape này có nên được tô đầy bằng nền của slide thay vì được chỉ định bằng kiểu dáng hoặc định dạng tô màu hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


Xác định xem autoshape này có nên được tô đầy bằng nền của slide thay vì được chỉ định bằng kiểu dáng hoặc định dạng tô màu hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


Thêm một TextFrame mới vào một shape. Nếu shape đã có TextFrame thì chỉ đơn giản thay đổi văn bản của nó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản mặc định cho một TextFrame mới. |

**Trả về:**
[ITextFrame](../../com.aspose.slides/itextframe) - Đối tượng [ITextFrame](../../com.aspose.slides/itextframe) mới.
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


Chỉ định nếu shape là một hộp văn bản.

--------------------

Nếu shape không được chỉ định là một hộp văn bản không có nghĩa là nó không thể có văn bản đính kèm. Hộp văn bản chỉ là một shape chuyên biệt với các thuộc tính cụ thể.

**Trả về:**
boolean