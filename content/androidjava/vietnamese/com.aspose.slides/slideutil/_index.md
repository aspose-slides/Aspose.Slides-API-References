---
title: SlideUtil
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cung cấp các phương thức giúp tìm kiếm shapes và văn bản trong một bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/slideutil/
---
**Kế thừa:**
java.lang.Object
```
public class SlideUtil
```

Cung cấp các phương thức giúp tìm kiếm shapes và văn bản trong một bản trình chiếu.
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | Tìm shape theo văn bản thay thế trong một bản trình chiếu PPTX. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | Tìm shape theo văn bản thay thế trên một slide trong bản trình chiếu PPTX. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | Tìm kiếm tất cả các shapes trên slide được chỉ định khớp với loại placeholder đã cho. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | Thay đổi vị trí của tất cả các shapes trên slide. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | Thay đổi vị trí của các shapes đã chọn trên slide. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | Thay đổi vị trí của tất cả các shapes trong group shape. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | Thay đổi vị trí của các shapes đã chọn trong group shape. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | Tìm và thay thế văn bản trong bản trình chiếu với định dạng đã cho |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | Tìm và thay thế văn bản trong bản trình chiếu với định dạng đã cho |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Trả về tất cả các text frames trên một slide trong bản trình chiếu PPTX. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | Trả về tất cả các text frames trên slide được chỉ định chứa văn bản đã cho. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Trả về tất cả các text frames trong bản trình chiếu PPTX. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | Chuyển đổi định dạng tệp nguồn sang [SaveFormat](../../com.aspose.slides/saveformat) tương ứng. |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```

### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```

Tìm shape theo văn bản thay thế trong một bản trình chiếu PPTX.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Bản trình chiếu đã được quét. |
| altText | java.lang.String | Văn bản thay thế của một shape. |

**Giá trị trả về:**
[IShape](../../com.aspose.slides/ishape) - Shape hoặc null.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```

Tìm shape theo văn bản thay thế trên một slide trong bản trình chiếu PPTX.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide đã được quét. |
| altText | java.lang.String | Văn bản thay thế của một shape. |

**Giá trị trả về:**
[IShape](../../com.aspose.slides/ishape) - Shape hoặc null.
### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```

Tìm kiếm tất cả các shapes trên slide được chỉ định khớp với loại placeholder đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide để tìm kiếm shapes. |
| placeholderType | byte | Loại placeholder để lọc shapes. |

**Giá trị trả về:**
com.aspose.slides.IShape[] - Mảng các đối tượng [IShape](../../com.aspose.slides/ishape) khớp với loại placeholder đã chỉ định.
### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```

Thay đổi vị trí của tất cả các shapes trên slide. Căn các shapes tới lề hoặc cạnh của slide hoặc căn chúng tương đối với nhau.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, true, pres.getSlides().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| alignmentType | int | Xác định loại căn chỉnh sẽ được áp dụng. |
| alignToSlide | boolean | Nếu true, các shape sẽ được căn tương đối với các cạnh của slide. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide cha. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```

Thay đổi vị trí của các shapes đã chọn trên slide. Căn các shapes tới lề hoặc cạnh của slide hoặc căn chúng tương đối với nhau.

--------------------

> ```
> Example:
>   
>   Presentation pres = new Presentation("pres.pptx");
>   try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape1 = slide.getShapes().get_Item(0);
>      IShape shape2 = slide.getShapes().get_Item(1);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, false, pres.getSlides().get_Item(0), new int[]
>      {
>          slide.getShapes().indexOf(shape1),
>          slide.getShapes().indexOf(shape2)
>      });
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| alignmentType | int | Xác định loại căn chỉnh sẽ được áp dụng. |
| alignToSlide | boolean | Nếu true, các shape sẽ được căn tương đối với các cạnh của slide. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide cha. |
| shapeIndexes | int[] | Các chỉ mục của shapes cần căn. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```

Thay đổi vị trí của tất cả các shapes trong group shape. Căn các shapes tới lề hoặc cạnh của slide hoặc căn chúng tương đối với nhau.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape) slide.getShapes().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| alignmentType | int | Xác định loại căn chỉnh sẽ được áp dụng. |
| alignToSlide | boolean | Nếu true, các shape sẽ được căn tương đối với các cạnh của slide. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Group shape cha. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```

Thay đổi vị trí của các shapes đã chọn trong group shape. Căn các shapes tới lề hoặc cạnh của slide hoặc căn chúng tương đối với nhau.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.getShapes().get_Item(0), new int[] { 0, 2 });
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| alignmentType | int | Xác định loại căn chỉnh sẽ được áp dụng. |
| alignToSlide | boolean | Nếu true, các shape sẽ được căn tương đối với các cạnh của slide. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Group shape cha. |
| shapeIndexes | int[] | Các chỉ mục của shapes cần căn. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```

Tìm và thay thế văn bản trong bản trình chiếu với định dạng đã cho

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Bản trình chiếu đã được quét. |
| withMasters | boolean | Xác định có quét các slide master hay không. |
| find | java.lang.String | Giá trị chuỗi cần tìm. |
| replace | java.lang.String | Giá trị chuỗi thay thế. ký tự của chuỗi tìm được |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```

Tìm và thay thế văn bản trong bản trình chiếu với định dạng đã cho

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Bản trình chiếu đã được quét. |
| withMasters | boolean | Xác định có quét các slide master hay không. |
| find | java.lang.String | Giá trị chuỗi cần tìm. |
| replace | java.lang.String | Giá trị chuỗi thay thế. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | Định dạng cho phần văn bản thay thế. Nếu null sẽ dùng định dạng của ký tự đầu tiên của chuỗi đã tìm |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```

Trả về tất cả các text frames trên một slide trong bản trình chiếu PPTX.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide đã được quét. |

**Giá trị trả về:**
com.aspose.slides.ITextFrame[] - Mảng các đối tượng [TextFrame](../../com.aspose.slides/textframe).

### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```

Trả về tất cả các text frames trên slide được chỉ định chứa văn bản đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide để tìm kiếm. |
| text | java.lang.String | Văn bản cần tìm trong các text frames. |
| checkPlaceholderText | boolean | Chỉ ra có bao gồm các text frames trống nhưng placeholder text của chúng chứa văn bản tìm kiếm hay không. |

**Giá trị trả về:**
com.aspose.slides.ITextFrame[] - Mảng các đối tượng [ITextFrame](../../com.aspose.slides/itextframe) chứa văn bản đã chỉ định.

### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```

Trả về tất cả các text frames trong bản trình chiếu PPTX.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Bản trình chiếu đã được quét. |
| withMasters | boolean | Xác định có quét các slide master hay không. |

**Giá trị trả về:**
com.aspose.slides.ITextFrame[] - Mảng các đối tượng [TextFrame](../../com.aspose.slides/textframe).

### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```

Chuyển đổi định dạng tệp nguồn sang [SaveFormat](../../com.aspose.slides/saveformat) tương ứng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| format | int | Định dạng tệp nguồn. |

**Giá trị trả về:**
int - Giá trị [SaveFormat](../../com.aspose.slides/saveformat) tương ứng.