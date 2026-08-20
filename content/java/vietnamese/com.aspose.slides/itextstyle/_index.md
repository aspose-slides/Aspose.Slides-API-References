---
title: ITextStyle
second_title: Tham khảo API Aspose.Slides cho Java
description: Các thuộc tính định dạng kiểu văn bản.
type: docs
url: /vi/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Các thuộc tính định dạng kiểu văn bản.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Nếu mức độ kiểu tồn tại, trả về nó, nếu không trả về null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Các thuộc tính mặc định của đoạn văn. |
| [getEffective()](#getEffective--) | Lấy dữ liệu định dạng kiểu văn bản có hiệu lực với sự kế thừa đã được áp dụng. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

Nếu mức độ kiểu tồn tại, trả về nó, nếu không trả về null.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số dựa trên số 0 của cấp độ. Phải nằm trong khoảng 0..8. |

**Returns:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Định dạng của cấp độ [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

Các thuộc tính mặc định của đoạn văn. Chỉ đọc [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Returns:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

Lấy dữ liệu định dạng kiểu văn bản có hiệu lực với sự kế thừa đã được áp dụng.

**Returns:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Một [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).