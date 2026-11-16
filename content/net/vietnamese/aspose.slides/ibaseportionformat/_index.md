---
title: IBasePortionFormat
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Lớp này chứa các thuộc tính định dạng phần văn bản. Khác với IPortionFormatEffectiveData./iportionformateffectivedata, tất cả các thuộc tính của lớp này đều có thể ghi.
type: docs
weight: 5330
url: /vi/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat giao diện

Lớp này chứa các thuộc tính định dạng phần văn bản. Khác với [`IPortionFormatEffectiveData`](../iportionformateffectivedata), tất cả các thuộc tính của lớp này đều có thể ghi.

```csharp
public interface IBasePortionFormat
```

## Thuộc tính

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Trả về hoặc đặt Id của một ngôn ngữ thay thế. Đọc/ghi String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ cho script phức tạp. Null có nghĩa là phông chữ chưa được xác định và nên kế thừa từ Master. Đọc/ghi [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ Đông Á. Null có nghĩa là phông chữ chưa được xác định và nên kế thừa từ Master. Đọc/ghi [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Trả về các thuộc tính EffectFormat của văn bản. Không áp dụng kế thừa. Chỉ đọc [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Trả về hoặc đặt văn bản lũy chỉ hoặc chỉ dưới. Giá trị từ -100% (chỉ dưới) đến 100% (lũy chỉ). **float.NaN** có nghĩa là giá trị chưa được xác định và nên kế thừa từ Master. Đọc/ghi Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Trả về các thuộc tính FillFormat của văn bản. Không áp dụng kế thừa. Chỉ đọc [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Xác định xem phông chữ có đậm hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Trả về hoặc đặt chiều cao phông chữ của một phần. **float.NaN** có nghĩa là chiều cao chưa được xác định và nên kế thừa từ Master. Đọc/ghi Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Xác định xem phông chữ có nghiêng hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Trả về hoặc đặt kiểu gạch chân của văn bản. Không áp dụng kế thừa. Đọc/ghi [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Trả về màu được dùng để tô sáng văn bản. Không áp dụng kế thừa. Chỉ đọc [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Xác định liệu kiểu gạch chân có các thuộc tính FillFormat riêng hoặc kế thừa từ FillFormat của văn bản. Đọc/ghi [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Xác định liệu kiểu gạch chân có các thuộc tính LineFormat riêng hoặc kế thừa từ LineFormat của văn bản. Đọc/ghi [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Trả về hoặc đặt kích thước phông chữ tối thiểu, mà ở đó kerning sẽ được bật. **float.NaN** có nghĩa là giá trị chưa được xác định và nên kế thừa từ Master. Đọc/ghi Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Xác định liệu các số có bỏ qua bố cục văn bản dọc đặc thù cho ngôn ngữ phía Đông không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Trả về hoặc đặt Id của một ngôn ngữ kiểm tra. Dùng để kiểm tra chính tả và ngữ pháp. Đọc/ghi String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ Latin. Null có nghĩa là phông chữ chưa được xác định và nên kế thừa từ Master. Đọc/ghi [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Trả về các thuộc tính LineFormat cho việc bao viền văn bản. Không áp dụng kế thừa. Chỉ đọc [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Xác định liệu chiều cao của văn bản có được chuẩn hoá hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Xác định liệu văn bản không được kiểm tra chính tả hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Trả về hoặc đặt mức tăng khoảng cách giữa các ký tự. **float.NaN** có nghĩa là giá trị chưa được xác định và nên kế thừa từ Master. Đọc/ghi Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Lấy hoặc đặt giá trị cho biết có bật kiểm tra chính tả cho phần văn bản này không. Khi thuộc tính này được đặt là false, việc kiểm tra chính tả cho các phần tử văn bản sẽ bị ẩn. Khi đặt là true, kiểm tra chính tả được cho phép. Giá trị mặc định là `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Trả về hoặc đặt kiểu gạch ngang (strikethrough) của văn bản. Không áp dụng kế thừa. Đọc/ghi [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ ký hiệu. Null có nghĩa là phông chữ chưa được xác định và nên kế thừa từ Master. Đọc/ghi [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Trả về hoặc đặt kiểu viết hoa của văn bản. Không áp dụng kế thừa. Đọc/ghi [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Trả về các thuộc tính FillFormat của đường gạch chân. Không áp dụng kế thừa. Chỉ đọc [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Trả về các thuộc tính LineFormat dùng để bao viền đường gạch chân. Không áp dụng kế thừa. Chỉ đọc [`ILineFormat`](../ilineformat). |

### Ghi chú

Lớp này được sử dụng để trả về và thao tác các thuộc tính định dạng phần văn bản được xác định cho phần cụ thể. Điều này có nghĩa là không có kế thừa nào được áp dụng khi lấy giá trị, vì vậy trong phần lớn các trường hợp bạn sẽ nhận được các giá trị mang nghĩa “không xác định”.

Để lấy các giá trị tham số định dạng hiệu lực bao gồm cả những giá trị kế thừa, bạn cần sử dụng phương thức [`GetEffective`](../iportionformat/geteffective) mà trả về một thể hiện [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Xem thêm

* không gian tên [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->