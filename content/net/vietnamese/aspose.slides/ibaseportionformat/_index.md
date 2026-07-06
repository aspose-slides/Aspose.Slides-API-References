---
title: IBasePortionFormat
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Lớp này chứa các thuộc tính định dạng phần văn bản. Không giống như IPortionFormatEffectiveData./iportionformateffectivedata, tất cả các thuộc tính của lớp này đều có thể ghi.
type: docs
weight: 5310
url: /vi/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat giao diện

This class contains the text portion formatting properties. Unlike [`IPortionFormatEffectiveData`](../iportionformateffectivedata), all properties of this class are writeable.

```csharp
public interface IBasePortionFormat
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Returns or sets the Id of an alternative language. Read/write String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ cho script phức tạp. Null có nghĩa là phông chữ chưa xác định và sẽ được kế thừa từ Master. Read/write [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ East Asian. Null có nghĩa là phông chữ chưa xác định và sẽ được kế thừa từ Master. Read/write [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Trả về các thuộc tính EffectFormat của văn bản. Không có kế thừa được áp dụng. Read-only [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Trả về hoặc đặt văn bản siêu chỉ hoặc chỉ dưới. Giá trị từ -100% (chỉ dưới) đến 100% (siêu chỉ). **float.NaN** có nghĩa là giá trị chưa xác định và sẽ được kế thừa từ Master. Read/write Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Trả về các thuộc tính FillFormat của văn bản. Không có kế thừa được áp dụng. Read-only [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Xác định xem phông chữ có dạng in đậm hay không. Không có kế thừa được áp dụng. Read/write [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Trả về hoặc đặt chiều cao phông chữ của một phần. **float.NaN** có nghĩa là chiều cao chưa xác định và sẽ được kế thừa từ Master. Read/write Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Xác định xem phông chữ có dạng in nghiêng hay không. Không có kế thừa được áp dụng. Read/write [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Trả về hoặc đặt kiểu gạch dưới của văn bản. Không có kế thừa được áp dụng. Read/write [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Trả về màu được dùng để đánh dấu văn bản. Không có kế thừa được áp dụng. Read-only [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Xác định xem kiểu gạch dưới có các thuộc tính FillFormat riêng hay kế thừa từ các thuộc tính FillFormat của văn bản. Read/write [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Xác định xem kiểu gạch dưới có các thuộc tính LineFormat riêng hay kế thừa từ các thuộc tính LineFormat của văn bản. Read/write [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Trả về hoặc đặt kích thước phông chữ tối thiểu, mà ở đó kerning sẽ được bật. **float.NaN** có nghĩa là giá trị chưa xác định và sẽ được kế thừa từ Master. Read/write Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Xác định liệu các số có nên bỏ qua bố cục văn bản dọc đặc thù của ngôn ngữ phía Đông hay không. Không có kế thừa được áp dụng. Read/write [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Trả về hoặc đặt Id của một ngôn ngữ kiểm tra. Được dùng để kiểm tra chính tả và ngữ pháp. Read/write String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ Latin. Null có nghĩa là phông chữ chưa xác định và sẽ được kế thừa từ Master. Read/write [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Trả về các thuộc tính LineFormat cho việc viền văn bản. Không có kế thừa được áp dụng. Read-only [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Xác định liệu chiều cao của văn bản có nên được chuẩn hoá hay không. Không có kế thừa được áp dụng. Read/write [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Xác định liệu văn bản không nên được kiểm tra hay không. Không có kế thừa được áp dụng. Read/write [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Trả về hoặc đặt mức tăng khoảng cách giữa các ký tự. **float.NaN** có nghĩa là giá trị chưa xác định và sẽ được kế thừa từ Master. Read/write Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Trả về hoặc đặt giá trị chỉ ra việc kiểm tra chính tả có được bật cho phần văn bản hay không. Khi thuộc tính này được đặt thành false, việc kiểm tra chính tả cho các phần tử văn bản sẽ bị ẩn. Khi đặt thành true, kiểm tra chính tả được cho phép. Giá trị mặc định là `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Trả về hoặc đặt kiểu gạch ngang văn bản. Không có kế thừa được áp dụng. Read/write [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ biểu tượng. Null có nghĩa là phông chữ chưa xác định và sẽ được kế thừa từ Master. Read/write [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Trả về hoặc đặt kiểu viết hoa của văn bản. Không có kế thừa được áp dụng. Read/write [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Trả về các thuộc tính FillFormat của đường gạch dưới. Không có kế thừa được áp dụng. Read-only [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Trả về các thuộc tính LineFormat được dùng để viền đường gạch dưới. Không có kế thừa được áp dụng. Read-only [`ILineFormat`](../ilineformat). |

### Ghi chú

Lớp này được dùng để trả về và thao tác các thuộc tính định dạng phần văn bản được định nghĩa cho phần cụ thể. Điều này có nghĩa là không có kế thừa được áp dụng khi lấy giá trị, vì vậy trong phần lớn các trường hợp bạn sẽ nhận được các giá trị có nghĩa là "không xác định".

Để lấy các giá trị tham số định dạng hiệu quả bao gồm cả những giá trị kế thừa, bạn cần sử dụng phương thức [`GetEffective`](../iportionformat/geteffective) mà trả về một đối tượng [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Xem thêm

* không gian tên [Aspose.Slides](../../aspose.slides)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->