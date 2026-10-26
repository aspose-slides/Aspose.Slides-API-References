---
title: ChartPortionFormat
second_title: Tham khảo API Aspose.Sildes cho .NET
description: Lớp này chứa các thuộc tính định dạng phần biểu đồ được sử dụng trong biểu đồ. Không giống như IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata, tất cả các thuộc tính của lớp này đều có thể ghi.
type: docs
weight: 1430
url: /vi/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat lớp

Lớp này chứa các thuộc tính định dạng phần biểu đồ được sử dụng trong biểu đồ. Không giống như [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata), tất cả các thuộc tính của lớp này đều có thể ghi.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Trả về hoặc đặt Id của ngôn ngữ thay thế. Đọc/ghi String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Cho phép lấy giao diện IPresentationComponent cơ bản. Chỉ đọc [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ script phức tạp. Null có nghĩa là phông chữ chưa xác định và nên được kế thừa từ Master. Đọc/ghi [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ Đông Á. Null có nghĩa là phông chữ chưa xác định và nên được kế thừa từ Master. Đọc/ghi [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Trả về các thuộc tính EffectFormat của văn bản. Không áp dụng kế thừa. Chỉ đọc [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Trả về hoặc đặt văn bản trên/dưới. Giá trị từ -100% (dưới) đến 100% (trên). **float.NaN** có nghĩa là giá trị chưa xác định và nên được kế thừa từ Master. Đọc/ghi Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Trả về các thuộc tính FillFormat của văn bản. Không áp dụng kế thừa. Chỉ đọc [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Xác định xem phông chữ có in đậm hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Trả về hoặc đặt chiều cao phông chữ của một phần. **float.NaN** có nghĩa là chiều cao chưa xác định và nên được kế thừa từ Master. Đọc/ghi Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Xác định xem phông chữ có in nghiêng hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Trả về hoặc đặt loại gạch chân văn bản. Không áp dụng kế thừa. Đọc/ghi [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Trả về màu được dùng để tô sáng văn bản. Không áp dụng kế thừa. Chỉ đọc [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Xác định xem kiểu gạch chân có các thuộc tính FillFormat riêng hay kế thừa từ thuộc tính FillFormat của văn bản. Đọc/ghi [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Xác định xem kiểu gạch chân có các thuộc tính LineFormat riêng hay kế thừa từ thuộc tính LineFormat của văn bản. Đọc/ghi [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Trả về hoặc đặt kích thước phông chữ tối thiểu, ở mức này kerning sẽ được bật. **float.NaN** có nghĩa là giá trị chưa xác định và nên được kế thừa từ Master. Đọc/ghi Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Xác định xem các số có nên bỏ qua bố cục văn bản dọc đặc thù cho ngôn ngữ phía đông hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Trả về hoặc đặt Id của ngôn ngữ kiểm tra. Được dùng để kiểm tra chính tả và ngữ pháp. Đọc/ghi String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ Latin. Null có nghĩa là phông chữ chưa xác định và nên được kế thừa từ Master. Đọc/ghi [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Trả về các thuộc tính LineFormat cho viền văn bản. Không áp dụng kế thừa. Chỉ đọc [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Xác định xem chiều cao của văn bản có nên được chuẩn hoá hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Xác định xem văn bản không nên được kiểm tra. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Trả về hoặc đặt mức tăng khoảng cách giữa các ký tự. **float.NaN** có nghĩa là giá trị chưa xác định và nên được kế thừa từ Master. Đọc/ghi Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Lấy hoặc đặt giá trị cho biết kiểm tra chính tả có được bật cho phần văn bản hay không. Khi thuộc tính này được đặt thành false, việc kiểm tra chính tả cho các phần tử văn bản sẽ bị bỏ qua. Khi đặt thành true, cho phép kiểm tra chính tả. Giá trị mặc định là `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Trả về hoặc đặt kiểu gạch xuyên của văn bản. Không áp dụng kế thừa. Đọc/ghi [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ biểu tượng. Null có nghĩa là phông chữ chưa xác định và nên được kế thừa từ Master. Đọc/ghi [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Trả về hoặc đặt kiểu viết hoa của văn bản. Không áp dụng kế thừa. Đọc/ghi [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Trả về các thuộc tính FillFormat của đường gạch chân. Không áp dụng kế thừa. Chỉ đọc [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Trả về các thuộc tính LineFormat được dùng để viền đường gạch chân. Không áp dụng kế thừa. Chỉ đọc [`ILineFormat`](../../aspose.slides/ilineformat). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | So sánh với đối tượng được chỉ định. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Trả về mã băm. |

### Ghi chú

Lớp này được sử dụng để trả về và thao tác các thuộc tính định dạng phần văn bản được định nghĩa cho phần cụ thể. Điều này có nghĩa là không áp dụng kế thừa khi lấy giá trị, vì vậy trong phần lớn các trường hợp bạn sẽ nhận được các giá trị có nghĩa là "không xác định".

Để lấy các giá trị tham số định dạng hiệu quả bao gồm cả những giá trị kế thừa, bạn cần sử dụng phương thức [`GetEffective`](../../aspose.slides/portionformat/geteffective) mà trả về một đối tượng [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### Xem thêm

* lớp [BasePortionFormat](../../aspose.slides/baseportionformat)
* giao diện [IChartPortionFormat](../ichartportionformat)
* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->