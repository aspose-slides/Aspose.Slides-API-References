---
title: BasePortionFormat
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Các thuộc tính định dạng đoạn văn bản chung.
type: docs
weight: 970
url: /vi/aspose.slides/baseportionformat/
---
## BasePortionFormat lớp

Các thuộc tính định dạng đoạn văn bản chung.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Trả về hoặc đặt Id của ngôn ngữ thay thế. Đọc/ghi String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Cho phép lấy giao diện IPresentationComponent cơ sở. Chỉ đọc [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ kịch bản phức tạp. Null có nghĩa là phông chữ chưa xác định và nên được kế thừa từ Master. Đọc/ghi [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ Đông Á. Null có nghĩa là phông chữ chưa xác định và nên được kế thừa từ Master. Đọc/ghi [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Trả về các thuộc tính EffectFormat của văn bản. Không áp dụng kế thừa. Chỉ đọc [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Trả về hoặc đặt văn bản trên hoặc dưới chỉ số. Giá trị từ -100% (chỉ số dưới) đến 100% (chỉ số trên). **float.NaN** có nghĩa là giá trị chưa xác định và nên được kế thừa từ Master. Đọc/ghi Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Trả về các thuộc tính FillFormat của văn bản. Không áp dụng kế thừa. Chỉ đọc [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Xác định liệu phông chữ có in đậm hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Trả về hoặc đặt chiều cao phông chữ của một đoạn. **float.NaN** có nghĩa là chiều cao chưa xác định và nên được kế thừa từ Master. Đọc/ghi Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Xác định liệu phông chữ có nghiêng hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Trả về hoặc đặt kiểu gạch chân của văn bản. Không áp dụng kế thừa. Đọc/ghi [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Trả về màu được dùng để làm nổi bật văn bản. Không áp dụng kế thừa. Chỉ đọc [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Xác định liệu kiểu gạch chân có thuộc tính FillFormat riêng hoặc kế thừa từ FillFormat của văn bản. Đọc/ghi [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Xác định liệu kiểu gạch chân có thuộc tính LineFormat riêng hoặc kế thừa từ LineFormat của văn bản. Đọc/ghi [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Trả về hoặc đặt kích thước phông chữ tối thiểu, ở mức mà kerning sẽ được bật. **float.NaN** có nghĩa là giá trị chưa xác định và nên được kế thừa từ Master. Đọc/ghi Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Xác định liệu các số nên bỏ qua bố trí văn bản dọc đặc thù cho ngôn ngữ phía Đông. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Trả về hoặc đặt Id của ngôn ngữ kiểm tra chính tả. Dùng để kiểm tra chính tả và ngữ pháp. Đọc/ghi String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ Latin. Null có nghĩa là phông chữ chưa xác định và nên được kế thừa từ Master. Đọc/ghi [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Trả về các thuộc tính LineFormat cho việc tạo viền văn bản. Không áp dụng kế thừa. Chỉ đọc [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Xác định liệu chiều cao của văn bản có được chuẩn hoá hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Xác định liệu văn bản không được kiểm tra chính tả. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Trả về hoặc đặt mức tăng khoảng cách giữa các ký tự. **float.NaN** có nghĩa là giá trị chưa xác định và nên được kế thừa từ Master. Đọc/ghi Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Lấy hoặc đặt giá trị chỉ ra liệu kiểm tra chính tả có được bật cho đoạn văn bản hay không. Khi thuộc tính này được đặt thành false, việc kiểm tra chính tả cho các phần tử văn bản sẽ bị tắt. Khi đặt thành true, việc kiểm tra chính tả được cho phép. Giá trị mặc định là `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Trả về hoặc đặt kiểu gạch xuyên qua của văn bản. Không áp dụng kế thừa. Đọc/ghi [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Trả về hoặc đặt thông tin phông ký hiệu. Null có nghĩa là phông chữ chưa xác định và nên được kế thừa từ Master. Đọc/ghi [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Trả về hoặc đặt kiểu viết hoa của văn bản. Không áp dụng kế thừa. Đọc/ghi [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Trả về các thuộc tính FillFormat của đường gạch chân. Không áp dụng kế thừa. Chỉ đọc [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Trả về các thuộc tính LineFormat được dùng để tạo viền cho đường gạch chân. Không áp dụng kế thừa. Chỉ đọc [`ILineFormat`](../ilineformat). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | So sánh với đối tượng được chỉ định. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Trả về mã băm. |

### Xem thêm

* lớp [PVIObject](../pviobject)
* giao diện [IBasePortionFormat](../ibaseportionformat)
* không gian tên [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->