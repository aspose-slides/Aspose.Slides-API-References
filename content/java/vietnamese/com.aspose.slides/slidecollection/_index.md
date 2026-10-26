---
title: SlideCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một bộ sưu tập slide.
type: docs
url: /vi/com.aspose.slides/slidecollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả giao diện được triển khai:**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

Biểu thị một bộ sưu tập các slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Lấy số phần tử thực tế chứa trong bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Thêm một bản sao của slide được chỉ định vào cuối bộ sưu tập. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Thêm một bản sao của slide được chỉ định vào cuối phần được chỉ định. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Chèn một bản sao của slide được chỉ định vào vị trí được chỉ định trong bộ sưu tập. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Thêm một slide trống mới vào cuối bộ sưu tập. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Chèn một bản sao của slide được chỉ định vào vị trí được chỉ định trong bộ sưu tập. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Thêm một bản sao của slide được chỉ định vào cuối bộ sưu tập. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Chèn một bản sao của slide được chỉ định vào vị trí được chỉ định trong bộ sưu tập. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Thêm một bản sao của slide nguồn được chỉ định vào cuối bộ sưu tập. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Chèn một bản sao của slide nguồn được chỉ định vào vị trí được chỉ định trong bộ sưu tập. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ mục được chỉ định trong bộ sưu tập. |
| [iterator()](#iterator--) | Trả về một enumerator cho phép duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
| [toArray()](#toArray--) | Tạo và trả về một mảng chứa tất cả các slide. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Tạo và trả về một mảng chứa tất cả các slide trong phạm vi được chỉ định. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Di chuyển slide từ bộ sưu tập đến vị trí được chỉ định. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Di chuyển các slide từ bộ sưu tập đến vị trí được chỉ định. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Trả về chỉ mục của slide được chỉ định trong bộ sưu tập. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Tạo slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Tạo slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập, cân nhắc các tùy chọn nhập PDF. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Tạo slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Tạo slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập bộ sưu tập có đồng bộ (an toàn đa luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về gốc đồng bộ hoá. |
### size() {#size--}
```
public final int size()
```

Lấy số phần tử thực tế chứa trong bộ sưu tập. Chỉ đọc int.

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Lấy phần tử tại chỉ mục được chỉ định. Chỉ đọc [Slide](../../com.aspose.slides/slide).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[ISlide](../../com.aspose.slides/islide)
### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

Thêm một bản sao của slide được chỉ định vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide để sao chép.

--------------------

Khi sao chép slide giữa các bản trình bày khác nhau, master của slide cũng có thể được sao chép. Registry nội bộ được sử dụng để theo dõi các master được sao chép tự động nhằm ngăn tạo nhiều bản sao của cùng một master slide. Việc sao chép thủ công các master slide sẽ không bị ngăn hay đăng ký. Nếu cần kiểm soát nhiều hơn quá trình sao chép, hãy sử dụng \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) hoặc \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) để sao chép slide, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) hoặc [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) để sao chép layout và [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) để sao chép master. |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide mới.
### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

Thêm một bản sao của slide được chỉ định vào cuối phần được chỉ định.

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
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide để sao chép. |
| section | [ISection](../../com.aspose.slides/isection) | Phần cho slide mới. |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide mới.
### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

Chèn một bản sao của slide được chỉ định vào vị trí được chỉ định trong bộ sưu tập.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // Khởi tạo lớp Presentation đại diện cho một tệp presentation file
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // Sao chép slide mong muốn tới cuối bộ sưu tập các slide trong cùng một presentation
>      ISlideCollection slds = pres.getSlides();
>      // Sao chép slide mong muốn tới chỉ mục xác định trong cùng một presentation
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // Ghi presentation đã chỉnh sửa ra đĩa
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // Khởi tạo lớp Presentation để tải tệp presentation nguồn
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Khởi tạo lớp Presentation cho PPTX đích (nơi slide sẽ được sao chép)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // Ghi presentation đích ra đĩa
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của slide mới. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide để sao chép.

--------------------

Khi sao chép slide giữa các bản trình bày khác nhau, master của slide cũng có thể được sao chép. Registry nội bộ được sử dụng để theo dõi các master được sao chép tự động nhằm ngăn tạo nhiều bản sao của cùng một master slide. Việc sao chép thủ công các master slide sẽ không bị ngăn hay đăng ký. Nếu cần kiểm soát nhiều hơn quá trình sao chép, hãy sử dụng \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) hoặc \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) để sao chép slide và [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) để sao chép master. |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide đã chèn.
### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
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
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Chèn một bản sao của slide được chỉ định vào vị trí được chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của slide mới. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout cho slide. |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide đã chèn.
### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Thêm một bản sao của slide được chỉ định vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide để sao chép. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout slide cho slide mới. |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide mới.
### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Chèn một bản sao của slide được chỉ định vào vị trí được chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của slide mới. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide để sao chép. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout slide cho slide mới. |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide đã chèn.
### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Thêm một bản sao của slide nguồn được chỉ định vào cuối bộ sưu tập. Layout phù hợp sẽ được tự động chọn từ master được chỉ định (layout phù hợp là layout có cùng Type hoặc Name với layout của slide nguồn). Nếu không có layout phù hợp thì layout của slide nguồn sẽ được sao chép (nếu allowCloneMissingLayout là true) hoặc sẽ ném PptxEditException (nếu allowCloneMissingLayout là false).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide để sao chép. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide cho slide mới. |
| allowCloneMissingLayout | boolean | Nếu không có layout phù hợp trong master được chỉ định thì layout của slide nguồn sẽ được sao chép (nếu allowCloneMissingLayout là true) hoặc sẽ ném PptxEditException (nếu allowCloneMissingLayout là false). |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide mới.
### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Chèn một bản sao của slide nguồn được chỉ định vào vị trí được chỉ định trong bộ sưu tập. Layout phù hợp sẽ được tự động chọn từ master được chỉ định (layout phù hợp là layout có cùng Type hoặc Name với layout của slide nguồn). Nếu không có layout phù hợp thì layout của slide nguồn sẽ được sao chép (nếu allowCloneMissingLayout là true) hoặc sẽ ném PptxEditException (nếu allowCloneMissingLayout là false).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của slide mới. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide để sao chép. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide cho slide mới. |
| allowCloneMissingLayout | boolean | Nếu không có layout phù hợp trong master được chỉ định thì layout của slide nguồn sẽ được sao chép (nếu allowCloneMissingLayout là true) hoặc sẽ ném PptxEditException (nếu allowCloneMissingLayout là false). |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide đã chèn.
### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Slide cần xóa khỏi bộ sưu tập. |

### removeAt(int index) {#removeAt-int-}
```
public final void remove(ISlide value)
```

Xóa phần tử tại chỉ mục được chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục (bắt đầu từ 0) của phần tử cần xóa. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Trả về một enumerator cho phép duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Một java.util.Iterator cho toàn bộ bộ sưu tập.
### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

Tạo và trả về một mảng chứa tất cả các slide.

**Trả về:**
com.aspose.slides.ISlide[] - Mảng của [Slide](../../com.aspose.slides/slide)
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

Tạo và trả về một mảng chứa tất cả các slide trong phạm vi được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| startIndex | int | Chỉ mục của slide đầu tiên cần thêm. |
| count | int | Số lượng slide cần thêm. |

**Trả về:**
com.aspose.slides.ISlide[] - Mảng của [Slide](../../com.aspose.slides/slide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

Di chuyển slide từ bộ sưu tập đến vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục đích. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide để di chuyển. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

Di chuyển các slide từ bộ sưu tập đến vị trí đã chỉ định. Các slide sẽ được đặt bắt đầu từ chỉ mục theo thứ tự chúng xuất hiện trong danh sách.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục đích. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Các slide để di chuyển. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

Trả về chỉ mục của slide được chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide để tìm. |

**Trả về:**
int - Chỉ mục của một slide hoặc -1 nếu slide không thuộc bộ sưu tập này.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

Tạo các slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập.

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
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Tạo các slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập, xem xét các tùy chọn nhập PDF.

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

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

Tạo các slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập.

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
| pdfStream | java.io.InputStream | Luồng sẽ được sử dụng làm nguồn của tài liệu PDF |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Tạo các slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập.

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
| pdfStream | java.io.InputStream | Luồng sẽ được sử dụng làm nguồn của tài liệu PDF |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Các tùy chọn cho việc nhập PDF |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Tạo các slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| htmlText | java.lang.String | HTML để thêm. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback được sử dụng để lấy các đối tượng bên ngoài. Nếu tham số này là null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | java.lang.String | URI của HTML đã chỉ định. Được sử dụng để giải quyết các liên kết tương đối. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

Tạo các slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| htmlText | java.lang.String | HTML để thêm. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Tạo các slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Đối tượng Stream sẽ được sử dụng làm nguồn của tệp HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback được sử dụng để lấy các đối tượng bên ngoài. Nếu tham số này là null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | java.lang.String | URI của HTML đã chỉ định. Được sử dụng để giải quyết các liên kết tương đối. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

Tạo các slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập.

--------------------

> ```
> // Tạo một thể hiện của lớp Presentation.
>  Presentation pres = new Presentation();
>  try {
>      String html = new String(Files.readAllBytes(Paths.get("file.html")));
>      // Gọi phương thức AddFromHtml và truyền tệp HTML.
>      pres.getSlides().addFromHtml(html);
>      // Sử dụng phương thức Save để lưu tệp dưới dạng tài liệu PowerPoint.
>      pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Đối tượng Stream sẽ được sử dụng làm nguồn của tệp HTML. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlText | java.lang.String | HTML để thêm. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback được sử dụng để lấy các đối tượng bên ngoài. Nếu tham số này là null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | java.lang.String | URI của HTML đã chỉ định. Được sử dụng để giải quyết các liên kết tương đối. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm.

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlText | java.lang.String | HTML để thêm. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback được sử dụng để lấy các đối tượng bên ngoài. Nếu tham số này là null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | java.lang.String | URI của HTML đã chỉ định. Được sử dụng để giải quyết các liên kết tương đối. |
| useSlideWithIndexAsStart | boolean | Cờ này xác định cách bắt đầu chèn: từ một slide mới hoặc từ slide có chỉ mục đã chỉ định. Nếu **true**, việc chèn dữ liệu sẽ bắt đầu từ một không gian trống trên slide có chỉ mục đã chỉ định. Nếu **false**, dữ liệu sẽ được thêm vào các slide đã tạo. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlText | java.lang.String | HTML để thêm. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlText | java.lang.String | HTML để thêm. |
| useSlideWithIndexAsStart | boolean | Cờ này xác định cách bắt đầu chèn: từ một slide mới hoặc từ slide có chỉ mục đã chỉ định. Nếu **true**, việc chèn dữ liệu sẽ bắt đầu từ một không gian trống trên slide có chỉ mục đã chỉ định. Nếu **false**, dữ liệu sẽ được thêm vào các slide đã tạo. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlStream | java.io.InputStream | Đối tượng Stream sẽ được sử dụng làm nguồn của tệp HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback được sử dụng để lấy các đối tượng bên ngoài. Nếu tham số này là null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | java.lang.String | URI của HTML đã chỉ định. Được sử dụng để giải quyết các liên kết tương đối. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlStream | java.io.InputStream | Đối tượng Stream sẽ được sử dụng làm nguồn của tệp HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback được sử dụng để lấy các đối tượng bên ngoài. Nếu tham số này là null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | java.lang.String | URI của HTML đã chỉ định. Được sử dụng để giải quyết các liên kết tương đối. |
| useSlideWithIndexAsStart | boolean | Cờ này xác định cách bắt đầu chèn: từ một slide mới hoặc từ slide có chỉ mục đã chỉ định. Nếu **true**, việc chèn dữ liệu sẽ bắt đầu từ một không gian trống trên slide có chỉ mục đã chỉ định. Nếu **false**, dữ liệu sẽ được thêm vào các slide đã tạo. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlStream | java.io.InputStream | Đối tượng Stream sẽ được sử dụng làm nguồn của tệp HTML. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlStream | java.io.InputStream | Đối tượng Stream sẽ được sử dụng làm nguồn của tệp HTML. |
| useSlideWithIndexAsStart | boolean | Cờ này xác định cách bắt đầu chèn: từ một slide mới hoặc từ slide có chỉ mục đã chỉ định. Nếu **true**, việc chèn dữ liệu sẽ bắt đầu từ một không gian trống trên slide có chỉ mục đã chỉ định. Nếu **false**, dữ liệu sẽ được thêm vào các slide đã tạo. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép tất cả các phần tử từ bộ sưu tập vào mảng đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết liệu việc truy cập bộ sưu tập có được đồng bộ (an toàn với đa luồng) hay không. Boolean chỉ đọc.

**Trả về:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về gốc đồng bộ. Object chỉ đọc.

**Trả về:**
java.lang.Object