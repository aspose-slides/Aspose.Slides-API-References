---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Đối tượng bất biến chứa các thuộc tính lấp đầy mẫu hiệu quả.
type: docs
url: /vi/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Đối tượng bất biến chứa các thuộc tính lấp đầy mẫu hiệu quả.

--------------------

Giao diện này được sử dụng như một phần của [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) và [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Trả về kiểu mẫu. |
| [getForeColor()](#getForeColor--) | Trả về màu mẫu tiền cảnh. |
| [getBackColor()](#getBackColor--) | Trả về màu mẫu nền. |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | Tạo hình ảnh gạch lát cho việc lấp đầy mẫu với các màu đã chỉ định. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Trả về kiểu mẫu. Chỉ đọc [PatternStyle](../../com.aspose.slides/patternstyle).

**Trả về:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```

Trả về màu mẫu tiền cảnh. Chỉ đọc java.awt.Color.

**Trả về:**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```

Trả về màu mẫu nền. Chỉ đọc java.awt.Color.

**Trả về:**
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```

Tạo hình ảnh gạch lát cho việc lấp đầy mẫu với các màu đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| background | java.awt.Color | Màu nền java.awt.Color cho mẫu. |
| foreground | java.awt.Color | Màu tiền cảnh java.awt.Color cho mẫu. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Mảnh [IImage](../../com.aspose.slides/iimage).