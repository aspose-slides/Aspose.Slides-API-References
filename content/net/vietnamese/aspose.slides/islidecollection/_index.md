---
title: ISlideCollection
second_title: Aspose.Sildes cho .NET Tham chiếu API
description: Biểu thị một bộ sưu tập các slide.
type: docs
weight: 7050
url: /vi/aspose.slides/islidecollection/
---
## ISlideCollection giao diện

Biểu thị một bộ sưu tập các slide.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Lấy phần tử tại chỉ mục được chỉ định. Chỉ đọc [`ISlide`](../islide). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Thêm một bản sao của slide được chỉ định vào cuối bộ sưu tập. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Thêm một bản sao của slide được chỉ định vào cuối bộ sưu tập. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Thêm một bản sao của slide được chỉ định vào cuối phần được chỉ định. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Thêm một bản sao của slide nguồn đã chỉ định vào cuối bộ sưu tập. Bố cục thích hợp sẽ được tự động chọn từ master được chỉ định (bố cục thích hợp là bố cục có cùng Type hoặc Name với bố cục của slide nguồn). Nếu không có bố cục thích hợp thì bố cục của slide nguồn sẽ được sao chép (nếu allowCloneMissingLayout là true) hoặc sẽ ném ra PptxEditException (nếu allowCloneMissingLayout là false). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Thêm một slide trống mới vào cuối bộ sưu tập. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Tạo các slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Tạo các slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Tạo các slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Tạo các slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Tạo các slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Tạo các slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Tạo các slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | Tạo các slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Tạo các slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Tạo các slide từ tài liệu PDF và thêm chúng vào cuối bộ sưu tập, cân nhắc các tùy chọn nhập PDF. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Trả về chỉ mục của slide đã chỉ định trong bộ sưu tập. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Chèn một bản sao của slide được chỉ định vào vị trí được chỉ định của bộ sưu tập. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Chèn một bản sao của slide được chỉ định vào vị trí được chỉ định của bộ sưu tập. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Chèn một bản sao của slide nguồn đã chỉ định vào vị trí được chỉ định của bộ sưu tập. Bố cục thích hợp sẽ được tự động chọn từ master được chỉ định (bố cục thích hợp là bố cục có cùng Type hoặc Name với bố cục của slide nguồn). Nếu không có bố cục thích hợp thì bố cục của slide nguồn sẽ được sao chép (nếu allowCloneMissingLayout là true) hoặc sẽ ném ra PptxEditException (nếu allowCloneMissingLayout là false). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Chèn một bản sao của slide được chỉ định vào vị trí được chỉ định của bộ sưu tập. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Xóa phần tử tại chỉ mục được chỉ định của bộ sưu tập. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Di chuyển slide từ bộ sưu tập đến vị trí được chỉ định. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Di chuyển các slide từ bộ sưu tập đến vị trí được chỉ định. Các slide sẽ được đặt bắt đầu từ chỉ mục theo thứ tự chúng xuất hiện trong danh sách. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Tạo và trả về một mảng chứa tất cả các slide. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Tạo và trả về một mảng chứa tất cả các slide trong khoảng được chỉ định. |

### Xem thêm

* giao diện [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* giao diện [ISlide](../islide)
* không gian tên [Aspose.Slides](../../aspose.slides)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->