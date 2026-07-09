---
title: BasePortionFormat
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Các thuộc tính định dạng phần văn bản chung.
type: docs
weight: 970
url: /vi/aspose.slides/baseportionformat/
---
## BasePortionFormat lớp

Các thuộc tính định dạng phần văn bản chung.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Trả về hoặc đặt Id của một ngôn ngữ thay thế. Đọc/ghi String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Cho phép lấy giao diện IPresentationComponent cơ bản. Chỉ đọc [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ script phức tạp. Null có nghĩa là phông chữ không được xác định và nên được kế thừa từ Master. Đọc/ghi [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ Đông Á. Null có nghĩa là phông chữ không được xác định và nên được kế thừa từ Master. Đọc/ghi [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Trả về các thuộc tính EffectFormat của văn bản. Không áp dụng kế thừa. Chỉ đọc [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Trả về hoặc đặt văn bản chỉ số trên hoặc chỉ số dưới. Giá trị từ -100% (chỉ số dưới) tới 100% (chỉ số trên). **float.NaN** có nghĩa là giá trị không xác định và nên được kế thừa từ Master. Đọc/ghi Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Trả về các thuộc tính FillFormat của văn bản. Không áp dụng kế thừa. Chỉ đọc [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Xác định xem phông chữ có in đậm hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Trả về hoặc đặt chiều cao phông chữ của một phần. **float.NaN** có nghĩa là chiều cao không xác định và nên được kế thừa từ Master. Đọc/ghi Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Xác định xem phông chữ có in nghiêng hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Trả về hoặc đặt kiểu gạch chân của văn bản. Không áp dụng kế thừa. Đọc/ghi [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Trả về màu được dùng để làm nổi bật văn bản. Không áp dụng kế thừa. Chỉ đọc [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Xác định xem kiểu gạch chân có thuộc tính FillFormat riêng hay kế thừa từ thuộc tính FillFormat của văn bản. Đọc/ghi [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Xác định xem kiểu gạch chân có thuộc tính LineFormat riêng hay kế thừa từ thuộc tính LineFormat của văn bản. Đọc/ghi [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Trả về hoặc đặt kích thước phông chữ tối thiểu, mà ở đó nên bật kerning. **float.NaN** có nghĩa là giá trị không xác định và nên được kế thừa từ Master. Đọc/ghi Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Xác định xem các số có nên bỏ qua bố cục văn bản dọc đặc thù cho ngôn ngữ phía đông hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Trả về hoặc đặt Id của một ngôn ngữ kiểm tra. Được sử dụng để kiểm tra chính tả và ngữ pháp. Đọc/ghi String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ Latin. Null có nghĩa là phông chữ không được xác định và nên được kế thừa từ Master. Đọc/ghi [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Trả về các thuộc tính LineFormat cho việc bao viền văn bản. Không áp dụng kế thừa. Chỉ đọc [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Xác định xem chiều cao của văn bản có nên được chuẩn hoá hay không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Xác định xem văn bản có nên không được kiểm tra không. Không áp dụng kế thừa. Đọc/ghi [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Trả về hoặc đặt gia tăng khoảng cách giữa các ký tự. **float.NaN** có nghĩa là giá trị không xác định và nên được kế thừa từ Master. Đọc/ghi Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Lấy hoặc đặt giá trị cho biết có bật kiểm tra chính tả cho phần văn bản hay không. Khi thuộc tính này được đặt là false, việc kiểm tra chính tả cho các thành phần văn bản sẽ bị tắt. Khi đặt là true, cho phép kiểm tra chính tả. Giá trị mặc định là `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Trả về hoặc đặt kiểu gạch xuyên qua của văn bản. Không áp dụng kế thừa. Đọc/ghi [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Trả về hoặc đặt thông tin phông chữ ký hiệu. Null có nghĩa là phông chữ không được xác định và nên được kế thừa từ Master. Đọc/ghi [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Trả về hoặc đặt kiểu viết hoa của văn bản. Không áp dụng kế thừa. Đọc/ghi [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Trả về các thuộc tính FillFormat của đường gạch chân. Không áp dụng kế thừa. Chỉ đọc [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Trả về các thuộc tính LineFormat được dùng để bao viền đường gạch chân. Không áp dụng kế thừa. Chỉ đọc [`ILineFormat`](../ilineformat). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | So sánh với đối tượng được chỉ định. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Trả về mã băm. |

### Xem thêm

* lớp [PVIObject](../pviobject)
* giao diện [IBasePortionFormat](../ibaseportionformat)
* không gian tên [Aspose.Slides](../../aspose.slides)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->