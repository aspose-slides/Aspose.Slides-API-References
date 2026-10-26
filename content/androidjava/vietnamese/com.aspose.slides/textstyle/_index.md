---
title: TextStyle
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Lớp này chứa các thuộc tính định dạng kiểu văn bản.
type: docs
url: /vi/com.aspose.slides/textstyle/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả giao diện được triển khai:**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

Lớp này chứa các thuộc tính định dạng kiểu văn bản.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | Nếu mức độ kiểu tồn tại, trả về nó, nếu không trả về null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Thuộc tính đoạn văn mặc định. |
| [getEffective()](#getEffective--) | Lấy dữ liệu định dạng kiểu văn bản thực tế với tính kế thừa được áp dụng. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. long chỉ đọc.

**Trả về:**
long
### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```

Nếu mức độ kiểu tồn tại, trả về nó, nếu không trả về null.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên số 0 của mức độ. Phải nằm trong khoảng 0..8. |

**Trả về:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Định dạng của mức [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```

Thuộc tính đoạn văn mặc định. Chỉ đọc [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Trả về:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```

Lấy dữ liệu định dạng kiểu văn bản thực tế với tính kế thừa được áp dụng.

--------------------

> ```
> This example demonstrates getting some of effective text style properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextStyleEffectiveData effectiveTextStyle = shape.getTextFrame().getTextFrameFormat().getTextStyle().getEffective();
>      for (int i = 0; i <= 8; i++)
>      {
>          IParagraphFormatEffectiveData effectiveStyleLevel = effectiveTextStyle.getLevel(i);
>          System.out.println("= Effective paragraph formatting for style level #" + i + " =");
>          System.out.println("Depth: " + effectiveStyleLevel.getDepth());
>          System.out.println("Indent: " + effectiveStyleLevel.getIndent());
>          System.out.println("Alignment: " + effectiveStyleLevel.getAlignment());
>          System.out.println("Font alignment: " + effectiveStyleLevel.getFontAlignment());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Một [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).