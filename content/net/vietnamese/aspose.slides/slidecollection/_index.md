---
title: SlideCollection
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Đại diện cho một bộ sưu tập các slide.
type: docs
weight: 9970
url: /vi/aspose.slides/slidecollection/
---
## Lớp SlideCollection

Đại diện cho một bộ sưu tập các slide.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Lấy số lượng phần tử thực tế có trong bộ sưu tập. Chỉ đọc Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Trả về giá trị cho biết liệu việc truy cập vào bộ sưu tập có được đồng bộ (an toàn với đa luồng) hay không. Chỉ đọc Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Lấy phần tử tại chỉ mục được chỉ định. Chỉ đọc [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Trả về gốc đồng bộ. Chỉ đọc Object. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Thêm một bản sao của slide được chỉ định vào cuối bộ sưu tập. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Thêm một bản sao của slide được chỉ định vào cuối bộ sưu tập. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Thêm một bản sao của slide được chỉ định vào cuối phần được chỉ định. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Thêm một bản sao của slide nguồn được chỉ định vào cuối bộ sưu tập. Bố cục thích hợp sẽ được tự động chọn từ master được chỉ định (bố cục thích hợp là bố cục có Type hoặc Name giống với bố cục của slide nguồn). Nếu không có bố cục thích hợp thì bố cục của slide nguồn sẽ được sao chép (nếu allowCloneMissingLayout là true) hoặc PptxEditException sẽ được ném ra (nếu allowCloneMissingLayout là false). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Thêm một slide trống mới vào cuối bộ sưu tập. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Tạo slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Tạo slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | Tạo slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Tạo slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Tạo slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập, xem xét các tùy chọn nhập PDF. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Trả về một enumerator để duyệt qua bộ sưu tập. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Trả về chỉ mục của slide được chỉ định trong bộ sưu tập. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Chèn một bản sao của slide được chỉ định vào vị trí đã chỉ định trong bộ sưu tập. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Chèn một bản sao của slide được chỉ định vào vị trí đã chỉ định trong bộ sưu tập. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Chèn một bản sao của slide nguồn được chỉ định vào vị trí đã chỉ định trong bộ sưu tập. Bố cục thích hợp sẽ được tự động chọn từ master được chỉ định (bố cục thích hợp là bố cục có Type hoặc Name giống với bố cục của slide nguồn). Nếu không có bố cục thích hợp thì bố cục của slide nguồn sẽ được sao chép (nếu allowCloneMissingLayout là true) hoặc PptxEditException sẽ được ném ra (nếu allowCloneMissingLayout là false). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Chèn một bản sao của slide được chỉ định vào vị trí đã chỉ định trong bộ sưu tập. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Tạo slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí đã chỉ định. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Xóa phần tử tại chỉ mục được chỉ định trong bộ sưu tập. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Di chuyển slide từ bộ sưu tập đến vị trí đã chỉ định. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Di chuyển các slide từ bộ sưu tập đến vị trí đã chỉ định. Các slide sẽ được đặt bắt đầu từ chỉ mục theo thứ tự chúng xuất hiện trong danh sách. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Tạo và trả về một mảng chứa tất cả các slide. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Tạo và trả về một mảng chứa tất cả các slide trong phạm vi được chỉ định. Chỉ mục của slide đầu tiên để thêm. Số lượng slide để thêm. |

### Xem thêm

* lớp [DomObject&lt;TParent&gt;](../domobject-1)
* lớp [Presentation](../presentation)
* giao diện [ISlideCollection](../islidecollection)
* không gian tên [Aspose.Slides](../../aspose.slides)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->