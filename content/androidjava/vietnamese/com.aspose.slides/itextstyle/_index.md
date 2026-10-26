---
title: ITextStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Thuộc tính định dạng kiểu văn bản.
type: docs
url: /vi/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Thuộc tính định dạng kiểu văn bản.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | If level of style exist returns it, otherwise returns null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Default paragraph propertiies. |
| [getEffective()](#getEffective--) | Gets effective text style formatting data with the inheritance applied. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

Nếu mức độ của kiểu tồn tại, trả về nó; nếu không, trả về null.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên số 0 của mức độ. Phải nằm trong khoảng 0..8. |

**Giá trị trả về:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Định dạng của mức [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

Thuộc tính mặc định của đoạn văn. Chỉ đọc [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Giá trị trả về:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

Lấy dữ liệu định dạng kiểu văn bản hiệu quả với tính kế thừa đã được áp dụng.

**Giá trị trả về:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Một [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).