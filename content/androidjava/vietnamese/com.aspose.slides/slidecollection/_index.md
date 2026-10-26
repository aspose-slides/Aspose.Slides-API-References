---
title: SlideCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một tập hợp các slide.
type: docs
url: /vi/com.aspose.slides/slidecollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

Mô tả một tập hợp các slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Lấy số phần tử thực tế chứa trong tập hợp. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục đã chỉ định. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Thêm một bản sao của slide đã chỉ định vào cuối tập hợp. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Thêm một bản sao của slide đã chỉ định vào cuối phần đã chỉ định. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Chèn một bản sao của slide đã chỉ định vào vị trí đã chỉ định trong tập hợp. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Thêm một slide trống mới vào cuối tập hợp. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Chèn một bản sao của slide đã chỉ định vào vị trí đã chỉ định trong tập hợp. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Thêm một bản sao của slide đã chỉ định vào cuối tập hợp. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Chèn một bản sao của slide đã chỉ định vào vị trí đã chỉ định trong tập hợp. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Thêm một bản sao của slide nguồn đã chỉ định vào cuối tập hợp. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Chèn một bản sao của slide nguồn đã chỉ định vào vị trí đã chỉ định trong tập hợp. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Xóa lần xuất hiện đầu tiên của đối tượng cụ thể khỏi tập hợp. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ mục đã chỉ định của tập hợp. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua tập hợp. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ tập hợp. |
| [toArray()](#toArray--) | Tạo và trả về một mảng chứa tất cả các slide. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Tạo và trả về một mảng chứa tất cả các slide trong phạm vi đã chỉ định. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Di chuyển slide từ tập hợp tới vị trí đã chỉ định. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Di chuyển các slide từ tập hợp tới vị trí đã chỉ định. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Trả về chỉ mục của slide đã chỉ định trong tập hợp. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Tạo slide từ tài liệu PDF và thêm chúng vào cuối tập hợp. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Tạo slide từ tài liệu PDF và thêm chúng vào cuối tập hợp theo tùy chọn nhập PDF. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Tạo slide từ tài liệu PDF và thêm chúng vào cuối tập hợp. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Tạo slide từ tài liệu PDF và thêm chúng vào cuối tập hợp. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tạo slide từ văn bản HTML và thêm chúng vào cuối tập hợp. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Tạo slide từ văn bản HTML và thêm chúng vào cuối tập hợp. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tạo slide từ văn bản HTML và thêm chúng vào cuối tập hợp. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Tạo slide từ văn bản HTML và thêm chúng vào cuối tập hợp. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tạo slide từ văn bản HTML và chèn chúng vào tập hợp tại vị trí đã chỉ định. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Tạo slide từ văn bản HTML và chèn chúng vào tập hợp tại vị trí đã chỉ định. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Tạo slide từ văn bản HTML và chèn chúng vào tập hợp tại vị trí đã chỉ định. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Tạo slide từ văn bản HTML và chèn chúng vào tập hợp tại vị trí đã chỉ định. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tạo slide từ văn bản HTML và chèn chúng vào tập hợp tại vị trí đã chỉ định. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Tạo slide từ văn bản HTML và chèn chúng vào tập hợp tại vị trí đã chỉ định. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Tạo slide từ văn bản HTML và chèn chúng vào tập hợp tại vị trí đã chỉ định. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Tạo slide từ văn bản HTML và chèn chúng vào tập hợp tại vị trí đã chỉ định. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ tập hợp vào mảng đã chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập tập hợp có được đồng bộ (thread-safe) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một synchronization root. |

### size() {#size--}
```
public final int size()
```

Lấy số phần tử thực tế chứa trong tập hợp. Chỉ đọc int.

**Trả về:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Lấy phần tử tại chỉ mục đã chỉ định. Chỉ đọc [Slide](../../com.aspose.slides/slide).

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

Thêm một bản sao của slide đã chỉ định vào cuối tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide để sao chép.

--------------------

Khi sao chép một slide giữa các bản trình bày khác nhau, master của slide cũng có thể được sao chép. Registry nội bộ được dùng để theo dõi các master được sao chép tự động nhằm ngăn việc tạo nhiều bản sao của cùng một master slide. Việc sao chép thủ công các master slide sẽ không bị ngăn chặn cũng không được ghi lại. Nếu bạn cần kiểm soát nhiều hơn quá trình sao chép, hãy sử dụng \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) hoặc \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) để sao chép slide, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) hoặc [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) để sao chép layout và [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) để sao chép master. |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide mới.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
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
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide để sao chép. |
| section | [ISection](../../com.aspose.slides/isection) | Phần cho slide mới. |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide mới.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

Chèn một bản sao của slide đã chỉ định vào vị trí đã chỉ định trong tập hợp.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // Khởi tạo lớp Presentation đại diện cho một tệp trình chiếu
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // Sao chép slide mong muốn tới cuối bộ sưu tập slide trong cùng một bản trình chiếu
>      ISlideCollection slds = pres.getSlides();
>      // Sao chép slide mong muốn tới chỉ mục đã chỉ định trong cùng một bản trình chiếu
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // Ghi bản trình chiếu đã sửa đổi ra đĩa
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // Khởi tạo lớp Presentation để tải tệp bản trình chiếu nguồn
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Khởi tạo lớp Presentation cho PPTX đích (nơi slide sẽ được sao chép)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // Ghi bản trình chiếu đích ra đĩa
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

Khi sao chép một slide giữa các bản trình bày khác nhau, master của slide cũng có thể được sao chép. Registry nội bộ được dùng để theo dõi các master được sao chép tự động nhằm ngăn việc tạo nhiều bản sao của cùng một master slide. Việc sao chép thủ công các master slide sẽ không bị ngăn chặn cũng không được ghi lại. Nếu bạn cần kiểm soát nhiều hơn quá trình sao chép, hãy sử dụng \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) hoặc \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) để sao chép slide và [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) để sao chép master. |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide đã chèn.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

Thêm một slide trống mới vào cuối tập hợp.

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

Chèn một bản sao của slide đã chỉ định vào vị trí đã chỉ định trong tập hợp.

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

Thêm một bản sao của slide đã chỉ định vào cuối tập hợp.

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

Chèn một bản sao của slide đã chỉ định vào vị trí đã chỉ định trong tập hợp.

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

Thêm một bản sao của slide nguồn đã chỉ định vào cuối tập hợp. Layout phù hợp sẽ được tự động chọn từ master đã chỉ định (layout phù hợp là layout có cùng Type hoặc Name với layout của slide nguồn). Nếu không có layout phù hợp thì layout của slide nguồn sẽ được sao chép (nếu allowCloneMissingLayout là true) hoặc sẽ ném PptxEditException (nếu allowCloneMissingLayout là false).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide để sao chép. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide cho slide mới. |
| allowCloneMissingLayout | boolean | Nếu không có layout phù hợp trong master đã chỉ định thì layout của slide nguồn sẽ được sao chép (nếu allowCloneMissingLayout là true) hoặc sẽ ném PptxEditException (nếu allowCloneMissingLayout là false). |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide mới.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Chèn một bản sao của slide nguồn đã chỉ định vào vị trí đã chỉ định trong tập hợp. Layout phù hợp sẽ được tự động chọn từ master đã chỉ định (layout phù hợp là layout có cùng Type hoặc Name với layout của slide nguồn). Nếu không có layout phù hợp thì layout của slide nguồn sẽ được sao chép (nếu allowCloneMissingLayout là true) hoặc sẽ ném PptxEditException (nếu allowCloneMissingLayout là false).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của slide mới. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Slide để sao chép. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide cho slide mới. |
| allowCloneMissingLayout | boolean | Nếu không có layout phù hợp trong master đã chỉ định thì layout của slide nguồn sẽ được sao chép (nếu allowCloneMissingLayout là true) hoặc sẽ ném PptxEditException (nếu allowCloneMissingLayout là false). |

**Trả về:**
[ISlide](../../com.aspose.slides/islide) - Slide đã chèn.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

Xóa lần xuất hiện đầu tiên của đối tượng cụ thể khỏi tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Slide cần xóa khỏi tập hợp. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa phần tử tại chỉ mục đã chỉ định của tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên zero của phần tử cần xóa. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Trả về một enumerator duyệt qua tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Một IGenericEnumerator có thể được dùng để duyệt qua tập hợp.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Trả về một java iterator cho toàn bộ tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Một java.util.Iterator cho toàn bộ tập hợp.

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

Tạo và trả về một mảng chứa tất cả các slide từ phạm vi đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| startIndex | int | Chỉ mục của slide đầu tiên cần thêm. |
| count | int | Số slide cần thêm. |

**Trả về:**
com.aspose.slides.ISlide[] - Mảng của [Slide](../../com.aspose.slides/slide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

Di chuyển slide từ tập hợp tới vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục đích. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide cần di chuyển. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

Di chuyển các slide từ tập hợp tới vị trí đã chỉ định. Các slide sẽ được đặt bắt đầu từ chỉ mục theo thứ tự chúng xuất hiện trong danh sách.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục đích. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Các slide cần di chuyển. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

Trả về chỉ mục của slide đã chỉ định trong tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide cần tìm. |

**Trả về:**
int - Chỉ mục của slide hoặc -1 nếu slide không thuộc tập hợp này.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

Tạo slide từ tài liệu PDF và thêm chúng vào cuối tập hợp.

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

Tạo slide từ tài liệu PDF và thêm chúng vào cuối tập hợp theo tùy chọn nhập PDF.

--------------------

> ```
> Ví dụ:
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
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Tùy chọn cho việc nhập PDF |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

Tạo slide từ tài liệu PDF và thêm chúng vào cuối tập hợp.

--------------------

> ```
> Ví dụ:
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

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Tạo slide từ tài liệu PDF và thêm chúng vào cuối tập hợp.

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
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Tùy chọn cho việc nhập PDF |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Tạo slide từ văn bản HTML và thêm chúng vào cuối tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| htmlText | java.lang.String | HTML cần thêm. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback dùng để lấy các đối tượng bên ngoài. Nếu tham số này null, sẽ bỏ qua tất cả các đối tượng bên ngoài. |
| uri | java.lang.String | URI của HTML đã chỉ định. Dùng để giải quyết các liên kết tương đối. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

Tạo slide từ văn bản HTML và thêm chúng vào cuối tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| htmlText | java.lang.String | HTML cần thêm. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Tạo slide từ văn bản HTML và thêm chúng vào cuối tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Đối tượng Stream sẽ được dùng làm nguồn của tệp HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback dùng để lấy các đối tượng bên ngoài. Nếu tham số này null, sẽ bỏ qua tất cả các đối tượng bên ngoài. |
| uri | java.lang.String | URI của HTML đã chỉ định. Dùng để giải quyết các liên kết tương đối. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

Tạo slide từ văn bản HTML và thêm chúng vào cuối tập hợp.

--------------------

> ```
> // Tạo một thể hiện của lớp Presentation.
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("file.html");
>          // Gọi phương thức AddFromHtml và truyền tệp HTML.
>          pres.getSlides().addFromHtml(fos);
>          // Sử dụng phương thức Save để lưu tệp dưới dạng tài liệu PowerPoint.
>          pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Đối tượng Stream sẽ được dùng làm nguồn của tệp HTML. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Tạo slide từ văn bản HTML và chèn chúng vào tập hợp tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlText | java.lang.String | HTML cần thêm. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback dùng để lấy các đối tượng bên ngoài. Nếu tham số này null, sẽ bỏ qua tất cả các đối tượng bên ngoài. |
| uri | java.lang.String | URI của HTML đã chỉ định. Dùng để giải quyết các liên kết tương đối. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm.

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Tạo slide từ văn bản HTML và chèn chúng vào tập hợp tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlText | java.lang.String | HTML cần thêm. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback dùng để lấy các đối tượng bên ngoài. Nếu tham số này null, sẽ bỏ qua tất cả các đối tượng bên ngoài. |
| uri | java.lang.String | URI của HTML đã chỉ định. Dùng để giải quyết các liên kết tương đối. |
| useSlideWithIndexAsStart | boolean | Cờ này xác định cách bắt đầu chèn: từ một slide mới hoặc từ slide có chỉ mục đã chỉ định. Nếu **true**, thì việc chèn dữ liệu sẽ bắt đầu từ không gian trống trên slide có chỉ mục đã chỉ định. Nếu **false**, thì dữ liệu sẽ được thêm vào các slide được tạo. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

Tạo slide từ văn bản HTML và chèn chúng vào tập hợp tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlText | java.lang.String | HTML cần thêm. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Tạo slide từ văn bản HTML và chèn chúng vào tập hợp tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlText | java.lang.String | HTML cần thêm. |
| useSlideWithIndexAsStart | boolean | Cờ này xác định cách bắt đầu chèn: từ một slide mới hoặc từ slide có chỉ mục đã chỉ định. Nếu **true**, thì việc chèn dữ liệu sẽ bắt đầu từ không gian trống trên slide có chỉ mục đã chỉ định. Nếu **false**, thì dữ liệu sẽ được thêm vào các slide được tạo. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Tạo slide từ văn bản HTML và chèn chúng vào tập hợp tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlStream | java.io.InputStream | Đối tượng Stream sẽ được dùng làm nguồn của tệp HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback dùng để lấy các đối tượng bên ngoài. Nếu tham số này null, sẽ bỏ qua tất cả các đối tượng bên ngoài. |
| uri | java.lang.String | URI của HTML đã chỉ định. Dùng để giải quyết các liên kết tương đối. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Tạo slide từ văn bản HTML và chèn chúng vào tập hợp tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlStream | java.io.InputStream | Đối tượng Stream sẽ được dùng làm nguồn của tệp HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback dùng để lấy các đối tượng bên ngoài. Nếu tham số này null, sẽ bỏ qua tất cả các đối tượng bên ngoài. |
| uri | java.lang.String | URI của HTML đã chỉ định. Dùng để giải quyết các liên kết tương đối. |
| useSlideWithIndexAsStart | boolean | Cờ này xác định cách bắt đầu chèn: từ một slide mới hoặc từ slide có chỉ mục đã chỉ định. Nếu **true**, thì việc chèn dữ liệu sẽ bắt đầu từ không gian trống trên slide có chỉ mục đã chỉ định. Nếu **false**, thì dữ liệu sẽ được thêm vào các slide được tạo. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Tạo slide từ văn bản HTML và chèn chúng vào tập hợp tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlStream | java.io.InputStream | Đối tượng Stream sẽ được dùng làm nguồn của tệp HTML. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Tạo slide từ văn bản HTML và chèn chúng vào tập hợp tại vị trí đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí chèn. |
| htmlStream | java.io.InputStream | Đối tượng Stream sẽ được dùng làm nguồn của tệp HTML. |
| useSlideWithIndexAsStart | boolean | Cờ này xác định cách bắt đầu chèn: từ một slide mới hoặc từ slide có chỉ mục đã chỉ định. Nếu **true**, thì việc chèn dữ liệu sẽ bắt đầu từ không gian trống trên slide có chỉ mục đã chỉ định. Nếu **false**, thì dữ liệu sẽ được thêm vào các slide được tạo. |

**Trả về:**
com.aspose.slides.ISlide[] - Các slide đã thêm

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép tất cả các phần tử từ tập hợp vào mảng đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết việc truy cập tập hợp có được đồng bộ (thread-safe) hay không. Chỉ đọc boolean.

**Trả về:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về một synchronization root. Chỉ đọc Object.

**Trả về:**
java.lang.Object