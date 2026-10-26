---
title: IAutoShape
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một AutoShape.
type: docs
url: /vi/com.aspose.slides/iautoshape/
---
**Tất cả các giao diện được triển khai:**
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
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Xác định liệu autoshape này có nên được tô đầy bằng nền của slide thay vì được chỉ định bởi style hoặc fill format. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Xác định liệu autoshape này có nên được tô đầy bằng nền của slide thay vì được chỉ định bởi style hoặc fill format. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Thêm một TextFrame mới vào shape. |
| [isTextBox()](#isTextBox--) | Chỉ định liệu shape là một text box hay không. |

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

Xác định liệu autoshape này có nên được tô đầy bằng nền của slide thay vì được chỉ định bởi style hoặc fill format. Đọc/ghi boolean.

**Trả về:**
boolean

### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```

Xác định liệu autoshape này có nên được tô đầy bằng nền của slide thay vì được chỉ định bởi style hoặc fill format. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```

Thêm một TextFrame mới vào shape. Nếu shape đã có TextFrame thì chỉ thay đổi văn bản của nó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản mặc định cho TextFrame mới. |

**Trả về:**
[ITextFrame](../../com.aspose.slides/itextframe) - Đối tượng [ITextFrame](../../com.aspose.slides/itextframe) mới.

### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```

Chỉ định liệu shape là một text box hay không.

--------------------

Nếu shape không được chỉ định là một text box không có nghĩa là nó không thể có văn bản được gắn vào. Một text box chỉ là một shape chuyên biệt với các thuộc tính cụ thể.

**Trả về:**
boolean