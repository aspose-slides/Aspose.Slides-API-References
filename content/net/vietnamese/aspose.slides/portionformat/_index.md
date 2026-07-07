---
title: PortionFormat
second_title: Aspose.Sildes cho Tham chiếu API .NET
description: Lớp này chứa các thuộc tính định dạng phần văn bản. Không giống như IPortionFormatEffectiveData./iportionformateffectivedata, tất cả các thuộc tính của lớp này đều có thể ghi.
type: docs
weight: 9490
url: /vi/aspose.slides/portionformat/
---
## Lớp PortionFormat

Lớp này chứa các thuộc tính định dạng phần văn bản. Không giống như [`IPortionFormatEffectiveData`](../iportionformateffectivedata), tất cả các thuộc tính của lớp này đều có thể ghi.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Hàm tạo

| Tên | Mô tả |
| --- | --- |
| [PortionFormat](portionformat)() | Khởi tạo một thể hiện mới của lớp [`PortionFormat`](../portionformat). |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Trả về hoặc đặt Id của ngôn ngữ thay thế. Đọc/ghi String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Cho phép lấy giao diện IPresentationComponent cơ bản. Chỉ đọc [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Trả về hoặc đặt định danh dấu trang. Đọc/ghi String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ kịch bản phức tạp. Null có nghĩa là phông chữ chưa xác định và nên được kế thừa từ Master. Đọc/ghi [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ Đông Á. Null có nghĩa là phông chữ chưa xác định và nên được kế thừa từ Master. Đọc/ghi [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Trả về các thuộc tính EffectFormat của văn bản. Không áp dụng kế thừa. Chỉ đọc [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Trả về hoặc đặt văn bản chỉ số trên hoặc chỉ số dưới. Giá trị từ -100% (chỉ số dưới) tới 100% (chỉ số trên). **float.NaN** có nghĩa là giá trị chưa xác định và nên được kế thừa từ Master. Đọc/ghi Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Trả về các thuộc tính FillFormat của văn bản. Không áp dụng kế thừa. Chỉ đọc [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Xác định xem phông chữ có in đậm hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Trả về hoặc đặt độ cao phông chữ của một phần. **float.NaN** có nghĩa là độ cao chưa xác định và nên được kế thừa từ Master. Đọc/ghi Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Xác định xem phông chữ có in nghiêng hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Trả về hoặc đặt kiểu gạch dưới của văn bản. Không áp dụng kế thừa. Đọc/ghi [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Trả về màu được sử dụng để làm nổi bật văn bản. Không áp dụng kế thừa. Chỉ đọc [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Trả về hoặc đặt siêu liên kết được định nghĩa cho cú nhấp chuột. Đọc/ghi [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Trình quản lý siêu liên kết. Chỉ đọc [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Trả về hoặc đặt siêu liên kết được định nghĩa cho di chuột qua. Đọc/ghi [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Xác định xem kiểu gạch dưới có thuộc tính FillFormat riêng hay kế thừa từ FillFormat của văn bản. Đọc/ghi [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Xác định xem kiểu gạch dưới có thuộc tính LineFormat riêng hay kế thừa từ LineFormat của văn bản. Đọc/ghi [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Trả về hoặc đặt kích thước phông chữ tối thiểu, ở đó kerning sẽ được bật. **float.NaN** có nghĩa là giá trị chưa xác định và nên được kế thừa từ Master. Đọc/ghi Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Xác định xem các số có nên bỏ qua bố cục văn bản dọc đặc thù của ngôn ngữ phía Đông không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Trả về hoặc đặt Id của ngôn ngữ kiểm tra. Được sử dụng để kiểm tra chính tả và ngữ pháp. Đọc/ghi String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ Latin. Null có nghĩa là phông chữ chưa xác định và nên được kế thừa từ Master. Đọc/ghi [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Trả về các thuộc tính LineFormat để viền văn bản. Không áp dụng kế thừa. Chỉ đọc [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Xác định xem chiều cao của văn bản có nên được chuẩn hoá không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Xác định xem văn bản có không nên được kiểm tra không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Xác định xem smart tag có nên được làm sạch không. Không áp dụng kế thừa. Đọc/ghi Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Trả về hoặc đặt mức gia tăng khoảng cách giữa các ký tự. **float.NaN** có nghĩa là giá trị chưa xác định và nên được kế thừa từ Master. Đọc/ghi Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Lấy hoặc đặt giá trị cho biết việc kiểm tra chính tả có được bật cho phần văn bản hay không. Khi thuộc tính này được đặt thành false, việc kiểm tra chính tả cho các phần tử văn bản sẽ bị ức chế. Khi đặt thành true, kiểm tra chính tả được cho phép. Giá trị mặc định là `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Trả về hoặc đặt kiểu gạch ngang của văn bản. Không áp dụng kế thừa. Đọc/ghi [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ biểu tượng. Null có nghĩa là phông chữ chưa xác định và nên được kế thừa từ Master. Đọc/ghi [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Trả về hoặc đặt kiểu chữ hoa/chữ thường cho văn bản. Không áp dụng kế thừa. Đọc/ghi [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Trả về các thuộc tính FillFormat của đường gạch dưới. Không áp dụng kế thừa. Chỉ đọc [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Trả về các thuộc tính LineFormat được dùng để viền đường gạch dưới. Không áp dụng kế thừa. Chỉ đọc [`ILineFormat`](../ilineformat). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | So sánh với đối tượng đã chỉ định. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Lấy dữ liệu định dạng phần hiệu quả với việc kế thừa đã được áp dụng. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Trả về mã băm. |

### Ghi chú

Lớp này được dùng để trả về và thao tác các thuộc tính định dạng phần văn bản được định nghĩa cho phần cụ thể. Điều này có nghĩa là không áp dụng kế thừa khi lấy giá trị, vì vậy trong hầu hết các trường hợp bạn sẽ nhận được các giá trị có nghĩa là "không xác định".

Để lấy các giá trị tham số định dạng hiệu quả bao gồm cả các giá trị kế thừa, bạn cần sử dụng phương thức [`GetEffective`](./geteffective) mà trả về một thể hiện [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Ví dụ

Các ví dụ dưới đây cho bạn biết cách gán phông chữ Latin cho phần của Paragraph trong PowerPoint Presentation.

```csharp
[C#]
//Khởi tạo một đối tượng presentation đại diện cho một tệp trình chiếu
using (Presentation pres = new Presentation("demo.pptx"))
{
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
    Paragraph paragraph = new Paragraph();
    Portion portion = new Portion("Theme text format");
    paragraph.Portions.Add(portion);
    shape.TextFrame.Paragraphs.Add(paragraph);
    // Aspose.Slides sử dụng các định danh đặc biệt này (tương tự như những định danh được sử dụng trong PowerPoint):
    // +mn-lt - Phông chữ Latin cho phần thân (Phông chữ Latin phụ)
    // +mj-lt - Phông chữ Latin cho tiêu đề (Phông chữ Latin chính)
    // +mn-ea - Phông chữ Đông Á cho phần thân (Phông chữ Đông Á phụ)
    // +mj-ea - Phông chữ Đông Á cho tiêu đề (Phông chữ Đông Á chính)
    portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Xem thêm

* lớp [BasePortionFormat](../baseportionformat)
* giao diện [IPortionFormat](../iportionformat)
* không gian tên [Aspose.Slides](../../aspose.slides)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->