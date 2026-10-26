---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Đối tượng bất biến chứa các thuộc tính đổ mẫu hiệu quả.
type: docs
url: /vi/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Đối tượng bất biến chứa các thuộc tính đổ mẫu hiệu quả.

--------------------

Giao diện này được sử dụng như một phần của [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) và [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Trả về kiểu mẫu. |
| [getForeColor()](#getForeColor--) | Trả về màu mẫu nền phía trước. |
| [getBackColor()](#getBackColor--) | Trả về màu mẫu nền phía sau. |
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | Tạo hình ảnh lát cho việc đổ mẫu với các màu được chỉ định. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Trả về kiểu mẫu. Chỉ đọc [PatternStyle](../../com.aspose.slides/patternstyle).

**Trả về:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```


Trả về màu mẫu nền phía trước. Chỉ đọc java.lang.Integer.

**Trả về:**
java.lang.Integer
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```


Trả về màu mẫu nền phía sau. Chỉ đọc java.lang.Integer.

**Trả về:**
java.lang.Integer
### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```


Tạo hình ảnh lát cho việc đổ mẫu với các màu được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| background | java.lang.Integer | java.lang.Integer nền cho mẫu. |
| foreground | java.lang.Integer | java.lang.Integer phía trước cho mẫu. |

**Trả về:**
[IImage](../../com.aspose.slides/iimage) - Ô [IImage](../../com.aspose.slides/iimage).