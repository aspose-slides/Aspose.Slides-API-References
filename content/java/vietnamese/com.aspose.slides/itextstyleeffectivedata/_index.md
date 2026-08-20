---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Đối tượng bất biến chứa các thuộc tính kiểu văn bản hiệu quả.
type: docs
url: /vi/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Đối tượng bất biến chứa các thuộc tính kiểu văn bản hiệu quả.

--------------------

Giao diện này được sử dụng cùng với giao diện [ITextStyle](../../com.aspose.slides/itextstyle) để trả về các giá trị định dạng hiệu quả có áp dụng kế thừa.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Trả về mức độ của kiểu văn bản hiệu quả. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Trả về các thuộc tính đoạn văn mặc định hiệu quả. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

Trả về mức độ của kiểu văn bản hiệu quả.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên số không của mức độ. Phải nằm trong khoảng 0..8. |

**Trả về:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Định dạng hiệu quả của mức [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

Trả về các thuộc tính đoạn văn mặc định hiệu quả. Chỉ đọc [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Trả về:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)