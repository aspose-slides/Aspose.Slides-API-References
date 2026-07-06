---
title: IBasePortionFormatEffectiveData
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Giao diện cơ sở cho các đối tượng bất biến chứa các thuộc tính định dạng phần văn bản hiệu lực.
type: docs
weight: 5320
url: /vi/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData giao diện

Giao diện cơ sở cho các đối tượng bất biến chứa các thuộc tính định dạng phần văn bản hiệu lực.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Trả về Id của một ngôn ngữ thay thế. Chỉ đọc String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Trả về thông tin phông chữ script phức tạp. Chỉ đọc [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Trả về thông tin phông chữ Đông Á. Chỉ đọc [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Trả về các thuộc tính EffectFormat của văn bản. Chỉ đọc [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Trả về văn bản chỉ số trên hoặc chỉ số dưới. Giá trị từ -100% (chỉ số dưới) đến 100% (chỉ số trên). Chỉ đọc Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Trả về các thuộc tính FillFormat của văn bản. Chỉ đọc [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Xác định xem phông chữ có in đậm hay không. Chỉ đọc Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Trả về chiều cao phông chữ của phần văn bản, tính bằng điểm. Chỉ đọc Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Xác định xem phông chữ có in nghiêng hay không. Chỉ đọc Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Trả về kiểu gạch chân văn bản. Chỉ đọc [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Trả về màu được dùng để tô sáng văn bản. Chỉ đọc Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Xác định xem kiểu gạch chân có các thuộc tính FillFormat riêng hay kế thừa từ các thuộc tính FillFormat của văn bản. Chỉ đọc Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Xác định xem kiểu gạch chân có các thuộc tính LineFormat riêng hay kế thừa từ các thuộc tính LineFormat của văn bản. Chỉ đọc Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Trả về kích thước phông chữ tối thiểu, khi đó nên bật kerning. Chỉ đọc Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Xác định xem các số có nên bỏ qua cách bố trí văn bản dọc đặc thù cho ngôn ngữ phương Đông hay không. Chỉ đọc Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Trả về Id của một ngôn ngữ. Chỉ đọc String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Trả về thông tin phông chữ Latin. Chỉ đọc [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Trả về các thuộc tính LineFormat cho việc viền văn bản. Chỉ đọc [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Xác định xem chiều cao của văn bản có nên được chuẩn hoá hay không. Chỉ đọc Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Xác định xem văn bản không nên được kiểm tra lỗi chính tả hay không. Chỉ đọc Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Xác định xem thẻ thông minh có nên được làm sạch hay không. Chỉ đọc Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Trả về khoảng cách tăng giữa các ký tự, tính bằng điểm. Chỉ đọc Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Trả về kiểu gạch ngang của văn bản. Chỉ đọc [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Trả về thông tin phông chữ ký hiệu. Chỉ đọc [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Trả về kiểu viết hoa của văn bản. Chỉ đọc [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Trả về các thuộc tính FillFormat của đường gạch chân. Chỉ đọc [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Trả về các thuộc tính LineFormat được dùng để viền đường gạch chân. Chỉ đọc [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Xem Thêm

* không gian tên [Aspose.Slides](../../aspose.slides)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->