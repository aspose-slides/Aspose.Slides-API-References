---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Đối tượng bất biến chứa các thuộc tính kiểu dạng hiệu quả.
type: docs
url: /vi/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Đối tượng bất biến chứa các thuộc tính kiểu dạng hiệu quả.

Giao diện này được sử dụng cùng với giao diện [ITextStyle](../../com.aspose.slides/itextstyle) để trả về các giá trị định dạng hiệu quả với kế thừa được áp dụng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Trả về mức độ của kiểu dạng hiệu quả. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Trả về các thuộc tính đoạn văn mặc định hiệu quả. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

Trả về mức độ của kiểu dạng hiệu quả.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên số 0 của mức độ. Phải nằm trong khoảng 0..8. |

**Trả về:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Định dạng hiệu quả của mức [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

Trả về các thuộc tính đoạn văn mặc định hiệu quả. Chỉ đọc [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Trả về:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)