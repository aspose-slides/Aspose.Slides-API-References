---
title: ChartPortionFormat
second_title: Tham khảo API Aspose.Sildes cho .NET
description: Lớp này chứa các thuộc tính định dạng phần biểu đồ được sử dụng trong biểu đồ. Không giống như IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata tất cả các thuộc tính của lớp này có thể ghi.
type: docs
weight: 1430
url: /vi/aspose.slides.charts/chartportionformat/
---
## Lớp ChartPortionFormat

Lớp này chứa các thuộc tính định dạng phần biểu đồ được sử dụng trong biểu đồ. Không giống như [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata), tất cả các thuộc tính của lớp này có thể ghi.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Trả về hoặc đặt Id của ngôn ngữ thay thế. Đọc/ghi String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Cho phép lấy giao diện cơ sở IPresentationComponent. Chỉ đọc [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ script phức tạp. Null nghĩa là phông chữ chưa xác định và nên được kế thừa từ Master. Đọc/ghi [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ Đông Á. Null nghĩa là phông chữ chưa xác định và nên được kế thừa từ Master. Đọc/ghi [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Trả về các thuộc tính EffectFormat của văn bản. Không áp dụng kế thừa. Chỉ đọc [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Trả về hoặc đặt văn bản siêu chỉ hoặc chỉ dưới. Giá trị từ -100% (chỉ dưới) tới 100% (siêu chỉ). **float.NaN** nghĩa là giá trị không xác định và nên được kế thừa từ Master. Đọc/ghi Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Trả về các thuộc tính FillFormat của văn bản. Không áp dụng kế thừa. Chỉ đọc [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Xác định xem phông chữ có đậm hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Trả về hoặc đặt chiều cao phông chữ của một phần. **float.NaN** nghĩa là chiều cao không xác định và nên được kế thừa từ Master. Đọc/ghi Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Xác định xem phông chữ có nghiêng hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Trả về hoặc đặt kiểu gạch chân văn bản. Không áp dụng kế thừa. Đọc/ghi [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Trả về màu được sử dụng để làm nổi bật văn bản. Không áp dụng kế thừa. Chỉ đọc [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Xác định xem kiểu gạch chân có thuộc tính FillFormat riêng hay kế thừa từ FillFormat của văn bản. Đọc/ghi [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Xác định xem kiểu gạch chân có thuộc tính LineFormat riêng hay kế thừa từ LineFormat của văn bản. Đọc/ghi [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Trả về hoặc đặt kích thước phông chữ tối thiểu, mà ở đó việc điều chỉnh kerning sẽ được bật. **float.NaN** nghĩa là giá trị không xác định và nên được kế thừa từ Master. Đọc/ghi Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Xác định xem các số có nên bỏ qua bố cục dọc đặc thù cho ngôn ngữ Đông Á của văn bản hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Trả về hoặc đặt Id của ngôn ngữ kiểm tra. Được sử dụng để kiểm tra chính tả và ngữ pháp. Đọc/ghi String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ Latin. Null nghĩa là phông chữ chưa xác định và nên được kế thừa từ Master. Đọc/ghi [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Trả về các thuộc tính LineFormat cho việc viền văn bản. Không áp dụng kế thừa. Chỉ đọc [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Xác định xem chiều cao của văn bản có nên được chuẩn hoá hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Xác định xem văn bản không nên được kiểm tra chính tả hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Trả về hoặc đặt mức tăng khoảng cách giữa các ký tự. **float.NaN** nghĩa là giá trị không xác định và nên được kế thừa từ Master. Đọc/ghi Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Lấy hoặc đặt giá trị cho biết kiểm tra chính tả có được bật cho phần văn bản hay không. Khi thuộc tính này được đặt là false, việc kiểm tra chính tả cho các phần tử văn bản sẽ bị ngừng. Khi đặt là true, kiểm tra chính tả được cho phép. Giá trị mặc định là `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Trả về hoặc đặt kiểu gạch ngang văn bản. Không áp dụng kế thừa. Đọc/ghi [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ biểu tượng. Null nghĩa là phông chữ chưa xác định và nên được kế thừa từ Master. Đọc/ghi [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Trả về hoặc đặt kiểu viết hoa văn bản. Không áp dụng kế thừa. Đọc/ghi [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Trả về các thuộc tính FillFormat của đường gạch chân. Không áp dụng kế thừa. Chỉ đọc [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Trả về các thuộc tính LineFormat được sử dụng để viền đường gạch chân. Không áp dụng kế thừa. Chỉ đọc [`ILineFormat`](../../aspose.slides/ilineformat). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | So sánh với đối tượng đã chỉ định. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Trả về mã băm. |

### Ghi chú

Lớp này được sử dụng để trả về và xử lý các thuộc tính định dạng phần văn bản được định nghĩa cho phần cụ thể. Điều này có nghĩa là không có kế thừa nào được áp dụng khi lấy giá trị, vì vậy trong hầu hết các trường hợp bạn sẽ nhận được các giá trị có nghĩa là “không xác định”.

Để lấy các giá trị tham số định dạng thực tế bao gồm các giá trị kế thừa, bạn cần sử dụng phương pháp [`GetEffective`](../../aspose.slides/portionformat/geteffective) mà trả về một thể hiện [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### Xem thêm

* lớp [BasePortionFormat](../../aspose.slides/baseportionformat)
* giao diện [IChartPortionFormat](../ichartportionformat)
* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->