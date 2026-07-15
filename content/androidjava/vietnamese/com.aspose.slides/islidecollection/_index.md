---
title: ISlideCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một bộ sưu tập các slide.
type: docs
url: /vi/com.aspose.slides/islidecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

Đại diện cho một bộ sưu tập các slide.
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục đã chỉ định. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Thêm một bản sao của slide đã chỉ định vào cuối bộ sưu tập. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Thêm một bản sao của slide đã chỉ định vào cuối phần đã chỉ định. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Chèn một bản sao của slide đã chỉ định vào vị trí đã chỉ định trong bộ sưu tập. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Thêm một slide trống mới vào cuối bộ sưu tập. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Chèn một bản sao của slide đã chỉ định vào vị trí đã chỉ định trong bộ sưu tập. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Thêm một bản sao của slide đã chỉ định vào cuối bộ sưu tập. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Chèn một bản sao của slide đã chỉ định vào vị trí đã chỉ định trong bộ sưu tập. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Thêm một bản sao của slide nguồn đã chỉ định vào cuối bộ sưu tập. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Chèn một bản sao của slide nguồn đã chỉ định vào vị trí đã chỉ định trong bộ sưu tập. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ mục đã chỉ định trong bộ sưu tập. |
| [toArray()](#toArray--) | Tạo và trả về một mảng chứa tất cả các slide. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Tạo và trả về một mảng chứa tất cả các slide từ phạm vi đã chỉ định. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Di chuyển slide khỏi bộ sưu tập tới vị trí đã chỉ định. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Di chuyển các slide khỏi bộ sưu tập tới vị trí đã chỉ định. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Trả về chỉ mục của slide đã chỉ định trong bộ sưu tập. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Tạo slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Tạo slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập, xét các tùy chọn nhập PDF. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Tạo slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Tạo slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

Lấy phần tử tại chỉ mục đã chỉ định. Chỉ đọc [ISlide](../../com.aspose.slides/islide).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

Thêm một bản sao của slide đã chỉ định vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide cần sao chép.

--------------------

Khi sao chép slide giữa các bài thuyết trình khác nhau, master của slide cũng có thể được sao chép. Registry nội bộ được dùng để theo dõi các master đã sao chép tự động nhằm ngăn ngừa việc tạo nhiều bản sao của cùng một master slide. Việc sao chép thủ công các master slide sẽ không bị ngăn cản cũng không được ghi nhận. Nếu bạn cần kiểm soát tốt hơn quá trình sao chép, hãy sử dụng \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) hoặc \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) để sao chép slide, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) hoặc [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) để sao chép layout và [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) để sao chép master. |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide mới.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
```

Thêm một bản sao của slide đã chỉ định vào cuối phần đã chỉ định.

--------------------

> ```
> IPresentation presentation = new Presentation();
>  try
>  {
>      presentation.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 50, 300, 100);
>      presentation.getSections().addSection("Section 1", presentation.getSlides().get_Item(0));
>      
>      ISection section2 = presentation.getSections().appendEmptySection("Section 2");
>      presentation.getSlides().addClone(presentation.getSlides().get_Item(0), section2);
>      
>      // Bây giờ phần thứ hai chứa một bản sao của slide đầu tiên.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide cần sao chép. |
| section | [ISection](../../com.aspose.slides/isection) | Phần cho slide mới. |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide mới.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

Chèn một bản sao của slide đã chỉ định vào vị trí đã chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của slide mới. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide cần sao chép.

--------------------

Khi sao chép slide giữa các bài thuyết trình khác nhau, master của slide cũng có thể được sao chép. Registry nội bộ được dùng để theo dõi các master đã sao chép tự động nhằm ngăn ngừa việc tạo nhiều bản sao của cùng một master slide. Việc sao chép thủ công các master slide sẽ không bị ngăn cản cũng không được ghi nhận. Nếu bạn cần kiểm soát tốt hơn quá trình sao chép, hãy sử dụng \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) hoặc \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) để sao chép slide và [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) để sao chép master. |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide đã chèn.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

Thêm một slide trống mới vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout cho slide. |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide đã thêm.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Chèn một bản sao của slide đã chỉ định vào vị trí đã chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của slide mới. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout cho slide. |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide đã chèn.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Thêm một bản sao của slide đã chỉ định vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide cần sao chép. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout slide cho slide mới. |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide mới.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Chèn một bản sao của slide đã chỉ định vào vị trí đã chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của slide mới. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide cần sao chép. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout slide cho slide mới. |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide đã chèn.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Thêm một bản sao của slide nguồn đã chỉ định vào cuối bộ sưu tập. Layout phù hợp sẽ được tự động chọn từ master đã chỉ định (layout phù hợp là layout có cùng Type hoặc Name với layout của slide nguồn). Nếu không có layout phù hợp, layout của slide nguồn sẽ được sao chép (nếu allowCloneMissingLayout là true) hoặc sẽ ném PptxEditException (nếu allowCloneMissingLayout là false).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide cần sao chép. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide cho slide mới. |
| allowCloneMissingLayout | boolean | Nếu không có layout phù hợp trong master đã chỉ định, layout của slide nguồn sẽ được sao chép (nếu true) hoặc ném PptxEditException (nếu false). |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide mới.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Chèn một bản sao của slide nguồn đã chỉ định vào vị trí đã chỉ định trong bộ sưu tập. Layout phù hợp sẽ được tự động chọn từ master đã chỉ định (layout phù hợp là layout có cùng Type hoặc Name với layout của slide nguồn). Nếu không có layout phù hợp, layout của slide nguồn sẽ được sao chép (nếu allowCloneMissingLayout là true) hoặc sẽ ném PptxEditException (nếu allowCloneMissingLayout là false).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của slide mới. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide cần sao chép. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide cho slide mới. |
| allowCloneMissingLayout | boolean | Nếu không có layout phù hợp trong master đã chỉ định, layout của slide nguồn sẽ được sao chép (nếu true) hoặc ném PptxEditException (nếu false). |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide đã chèn.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Slide cần xóa khỏi bộ sưu tập. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa phần tử tại chỉ mục đã chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên 0 của phần tử cần xóa. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

Tạo và trả về một mảng chứa tất cả các slide.

**Trả về:**
com.aspose.slides.ISlide[] - Mảng của [ISlide](../../com.aspose.slides/islide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

Tạo và trả về một mảng chứa tất cả các slide từ phạm vi đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| startIndex | int | Chỉ mục của slide đầu tiên cần thêm. |
| count | int | Số lượng slide cần thêm. |

**Trả về:**
com.aspose.slides.ISlide[] - Mảng của [ISlide](../../com.aspose.slides/islide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

Di chuyển slide khỏi bộ sưu tập tới vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục mục tiêu. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide cần di chuyển. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

Di chuyển các slide khỏi bộ sưu tập tới vị trí đã chỉ định. Các slide sẽ được đặt bắt đầu từ chỉ mục theo thứ tự xuất hiện trong danh sách.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục mục tiêu. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Các slide cần di chuyển. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

Trả về chỉ mục của slide đã chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide cần tìm. |

**Trả về:**
int - Chỉ mục của slide hoặc -1 nếu slide không thuộc bộ sưu tập này.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
```

Tạo slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getSlides().addFromPdf("document.pdf");
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| path | java.lang.String | Đường dẫn tới tài liệu PDF |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Tạo slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập, xét các tùy chọn nhập PDF.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
>      pres.getSlides().addFromPdf("document.pdf", pdfImportOptions);
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| path | java.lang.String | Đường dẫn tới tài liệu PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Các tùy chọn cho việc nhập PDF |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Tạo slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream, pdfImportOptions);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Luồng sẽ được dùng làm nguồn của tài liệu PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Các tùy chọn cho việc nhập PDF |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

Tạo slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Luồng sẽ được dùng làm nguồn của tài liệu PDF |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| htmlText | java.lang.String | HTML cần thêm. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback dùng để lấy các đối tượng bên ngoài. Nếu tham số này là null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | java.lang.String | URI của HTML đã chỉ định. Dùng để giải quyết các liên kết tương đối. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| htmlText | java.lang.String | HTML cần thêm. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Đối tượng Stream sẽ được dùng làm nguồn của tệp HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback dùng để lấy các đối tượng bên ngoài. Nếu tham số này là null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | java.lang.String | URI của HTML đã chỉ định. Dùng để giải quyết các liên kết tương đối. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Đối tượng Stream sẽ được dùng làm nguồn của tệp HTML. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlText | java.lang.String | HTML cần thêm. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback dùng để lấy các đối tượng bên ngoài. Nếu tham số này là null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | java.lang.String | URI của HTML đã chỉ định. Dùng để giải quyết các liên kết tương đối. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlText | java.lang.String | HTML cần thêm. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlStream | java.io.InputStream | Đối tượng Stream sẽ được dùng làm nguồn của tệp HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback dùng để lấy các đối tượng bên ngoài. Nếu tham số này là null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | java.lang.String | URI của HTML đã chỉ định. Dùng để giải quyết các liên kết tương đối. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlStream | java.io.InputStream | Đối tượng Stream sẽ được dùng làm nguồn của tệp HTML. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlText | java.lang.String | HTML cần thêm. |
| useSlideWithIndexAsStart | boolean | Cờ này xác định cách bắt đầu chèn: từ một slide mới hoặc từ slide có chỉ mục đã chỉ định. Nếu **true**, dữ liệu sẽ được chèn bắt đầu từ không gian trống trên slide có chỉ mục đã chỉ định. Nếu **false**, dữ liệu sẽ được thêm vào các slide được tạo. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlText | java.lang.String | HTML cần thêm. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback dùng để lấy các đối tượng bên ngoài. Nếu tham số này là null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | java.lang.String | URI của HTML đã chỉ định. Dùng để giải quyết các liên kết tương đối. |
| useSlideWithIndexAsStart | boolean | Cờ này xác định cách bắt đầu chèn: từ một slide mới hoặc từ slide có chỉ mục đã chỉ định. Nếu **true**, dữ liệu sẽ được chèn bắt đầu từ không gian trống trên slide có chỉ mục đã chỉ định. Nếu **false**, dữ liệu sẽ được thêm vào các slide được tạo. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm.

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlStream | java.io.InputStream | Đối tượng Stream sẽ được dùng làm nguồn của tệp HTML. |
| useSlideWithIndexAsStart | boolean | Cờ này xác định cách bắt đầu chèn: từ một slide mới hoặc từ slide có chỉ mục đã chỉ định. Nếu **true**, dữ liệu sẽ được chèn bắt đầu từ không gian trống trên slide có chỉ mục đã chỉ định. Nếu **false**, dữ liệu sẽ được thêm vào các slide được tạo. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlStream | java.io.InputStream | Đối tượng Stream sẽ được dùng làm nguồn của tệp HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback dùng để lấy các đối tượng bên ngoài. Nếu tham số này là null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | java.lang.String | URI của HTML đã chỉ định. Dùng để giải quyết các liên kết tương đối. |
| useSlideWithIndexAsStart | boolean | Cờ này xác định cách bắt đầu chèn: từ một slide mới hoặc từ slide có chỉ mục đã chỉ định. Nếu **true**, dữ liệu sẽ được chèn bắt đầu từ không gian trống trên slide có chỉ mục đã chỉ định. Nếu **false**, dữ liệu sẽ được thêm vào các slide được tạo. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm.