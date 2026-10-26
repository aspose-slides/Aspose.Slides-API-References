---
title: SlideUtil
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cung cấp các phương thức giúp tìm kiếm các shape và văn bản trong bản trình bày.
type: docs
url: /vi/com.aspose.slides/slideutil/
---
**Kế thừa:**
java.lang.Object
```
public class SlideUtil
```

Cung cấp các phương thức giúp tìm kiếm các shape và văn bản trong một bản trình bày.

## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | Tìm shape theo văn bản thay thế trong một bản trình bày PPTX. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | Tìm shape theo văn bản thay thế trên một slide trong bản trình bày PPTX. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | Tìm kiếm tất cả các shape trên slide được chỉ định phù hợp với loại placeholder đã cho. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | Thay đổi vị trí của tất cả các shape trên slide. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | Thay đổi vị trí của các shape đã chọn trên slide. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | Thay đổi vị trí của tất cả các shape trong group shape. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | Thay đổi vị trí của các shape đã chọn trong group shape. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | Tìm và thay thế văn bản trong bản trình bày với định dạng đã cho |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | Tìm và thay thế văn bản trong bản trình bày với định dạng đã cho |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Trả về tất cả các khung văn bản trên một slide trong bản trình bày PPTX. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | Trả về tất cả các khung văn bản trên slide chỉ định chứa văn bản đã cho. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Trả về tất cả các khung văn bản trong bản trình bày PPTX. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | Chuyển đổi định dạng tệp nguồn sang [SaveFormat](../../com.aspose.slides/saveformat) tương ứng. |

### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```

### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```

Tìm shape theo văn bản thay thế trong một bản trình bày PPTX.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Bản trình bày đã quét. |
| altText | java.lang.String | Văn bản thay thế của một shape. |

**Trả về:**
[IShape](../../com.aspose.slides/ishape) - Shape hoặc null.

### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```

Tìm shape theo văn bản thay thế trên một slide trong bản trình bày PPTX.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide đã quét. |
| altText | java.lang.String | Văn bản thay thế của một shape. |

**Trả về:**
[IShape](../../com.aspose.slides/ishape) - Shape hoặc null.

### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```

Tìm kiếm tất cả các shape trên slide được chỉ định phù hợp với loại placeholder đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide để tìm kiếm các shape. |
| placeholderType | byte | Loại placeholder để lọc các shape. |

**Trả về:**
com.aspose.slides.IShape[] - Một mảng các đối tượng [IShape](../../com.aspose.slides/ishape) phù hợp với loại placeholder đã chỉ định.

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```

Thay đổi vị trí của tất cả các shape trên slide. Căn các shape vào lề hoặc cạnh của slide hoặc căn chúng tương đối với nhau.

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
| alignToSlide | boolean | Nếu true, các shape sẽ được căn so với các cạnh của slide. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide cha. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```

Thay đổi vị trí của các shape đã chọn trên slide. Căn các shape vào lề hoặc cạnh của slide hoặc căn chúng tương đối với nhau.

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
| alignToSlide | boolean | Nếu true, các shape sẽ được căn so với các cạnh của slide. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide cha. |
| shapeIndexes | int[] | Chỉ mục của các shape cần được căn. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```

Thay đổi vị trí của tất cả các shape trong group shape. Căn các shape vào lề hoặc cạnh của slide hoặc căn chúng tương đối với nhau.

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
| alignToSlide | boolean | Nếu true, các shape sẽ được căn so với các cạnh của slide. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Group shape cha. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```

Thay đổi vị trí của các shape đã chọn trong group shape. Căn các shape vào lề hoặc cạnh của slide hoặc căn chúng tương đối với nhau.

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
| alignToSlide | boolean | Nếu true, các shape sẽ được căn so với các cạnh của slide. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Group shape cha. |
| shapeIndexes | int[] | Chỉ mục của các shape cần được căn. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```

Tìm và thay thế văn bản trong bản trình bày với định dạng đã cho

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
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Bản trình bày đã quét. |
| withMasters | boolean | Xác định có nên quét các slide master hay không. |
| find | java.lang.String | Giá trị chuỗi cần tìm. |
| replace | java.lang.String | Giá trị chuỗi để thay thế. ký tự của chuỗi được tìm. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```

Tìm và thay thế văn bản trong bản trình bày với định dạng đã cho

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
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Bản trình bày đã quét. |
| withMasters | boolean | Xác định có nên quét các slide master hay không. |
| find | java.lang.String | Giá trị chuỗi cần tìm. |
| replace | java.lang.String | Giá trị chuỗi để thay thế. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | Định dạng cho phần văn bản cần thay thế. Nếu null thì sẽ sử dụng định dạng của ký tự đầu tiên của chuỗi đã tìm. |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```

Trả về tất cả các khung văn bản trên một slide trong bản trình bày PPTX.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide đã quét. |

**Trả về:**
com.aspose.slides.ITextFrame[] - Mảng các đối tượng [TextFrame](../../com.aspose.slides/textframe).

### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```

Trả về tất cả các khung văn bản trên slide chỉ định chứa văn bản đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide để tìm kiếm. |
| text | java.lang.String | Văn bản để tìm kiếm trong các khung văn bản. |
| checkPlaceholderText | boolean | Cho biết có bao gồm các khung văn bản rỗng nhưng có placeholder chứa văn bản tìm kiếm hay không. |

**Trả về:**
com.aspose.slides.ITextFrame[] - Mảng các đối tượng [ITextFrame](../../com.aspose.slides/itextframe) chứa văn bản được chỉ định.

### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```

Trả về tất cả các khung văn bản trong bản trình bày PPTX.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Bản trình bày đã quét. |
| withMasters | boolean | Xác định có nên quét các slide master hay không. |

**Trả về:**
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

**Trả về:**
int - Giá trị [SaveFormat](../../com.aspose.slides/saveformat) tương ứng.