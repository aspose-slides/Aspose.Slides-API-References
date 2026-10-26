---
title: BasePortionFormat
second_title: Tham chiếu API Aspose.Slides cho Java
description: Các thuộc tính định dạng phần văn bản chung.
type: docs
url: /vi/com.aspose.slides/baseportionformat/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

Các thuộc tính định dạng phần văn bản chung.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | Trả về các thuộc tính LineFormat cho việc viền văn bản. |
| [getFillFormat()](#getFillFormat--) | Trả về các thuộc tính FillFormat của văn bản. |
| [getEffectFormat()](#getEffectFormat--) | Trả về các thuộc tính EffectFormat của văn bản. |
| [getHighlightColor()](#getHighlightColor--) | Trả về màu được dùng để làm nổi bật văn bản. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Trả về các thuộc tính LineFormat được dùng để viền đường gạch dưới. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Trả về các thuộc tính FillFormat của đường gạch dưới. |
| [getFontBold()](#getFontBold--) | Xác định xem phông chữ có in đậm hay không. |
| [setFontBold(byte value)](#setFontBold-byte-) | Xác định xem phông chữ có in đậm hay không. |
| [getFontItalic()](#getFontItalic--) | Xác định xem phông chữ có nghiêng hay không. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Xác định xem phông chữ có nghiêng hay không. |
| [getKumimoji()](#getKumimoji--) | Xác định xem các số có nên bỏ qua bố cục văn bản dọc đặc trưng cho ngôn ngữ phía Đông không. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Xác định xem các số có nên bỏ qua bố cục văn bản dọc đặc trưng cho ngôn ngữ phía Đông không. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Xác định xem chiều cao của văn bản có nên được chuẩn hoá không. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Xác định xem chiều cao của văn bản có nên được chuẩn hoá không. |
| [getProofDisabled()](#getProofDisabled--) | Xác định xem văn bản không nên được kiểm tra lỗi chính tả hay không. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Xác định xem văn bản không nên được kiểm tra lỗi chính tả hay không. |
| [getFontUnderline()](#getFontUnderline--) | Trả về hoặc thiết lập kiểu gạch dưới của văn bản. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Trả về hoặc thiết lập kiểu gạch dưới của văn bản. |
| [getTextCapType()](#getTextCapType--) | Trả về hoặc thiết lập kiểu chữ in hoa/chữ thường của văn bản. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Trả về hoặc thiết lập kiểu chữ in hoa/chữ thường của văn bản. |
| [getStrikethroughType()](#getStrikethroughType--) | Trả về hoặc thiết lập kiểu gạch ngang của văn bản. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Trả về hoặc thiết lập kiểu gạch ngang của văn bản. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Xác định xem kiểu gạch dưới có các thuộc tính LineFormat riêng hay kế thừa từ các thuộc tính LineFormat của văn bản. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Xác định xem kiểu gạch dưới có các thuộc tính LineFormat riêng hay kế thừa từ các thuộc tính LineFormat của văn bản. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Xác định xem kiểu gạch dưới có các thuộc tính FillFormat riêng hay kế thừa từ các thuộc tính FillFormat của văn bản. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Xác định xem kiểu gạch dưới có các thuộc tính FillFormat riêng hay kế thừa từ các thuộc tính FillFormat của văn bản. |
| [getFontHeight()](#getFontHeight--) | Trả về hoặc thiết lập chiều cao phông chữ của một phần. |
| [setFontHeight(float value)](#setFontHeight-float-) | Trả về hoặc thiết lập chiều cao phông chữ của một phần. |
| [getLatinFont()](#getLatinFont--) | Trả về hoặc thiết lập thông tin phông chữ Latin. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Trả về hoặc thiết lập thông tin phông chữ Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Trả về hoặc thiết lập thông tin phông chữ Đông Á. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Trả về hoặc thiết lập thông tin phông chữ Đông Á. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Trả về hoặc thiết lập thông tin phông chữ script phức tạp. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Trả về hoặc thiết lập thông tin phông chữ script phức tạp. |
| [getSymbolFont()](#getSymbolFont--) | Trả về hoặc thiết lập thông tin phông chữ ký hiệu. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Trả về hoặc thiết lập thông tin phông chữ ký hiệu. |
| [getEscapement()](#getEscapement--) | Trả về hoặc thiết lập văn bản trên chỉ số hoặc dưới chỉ số. |
| [setEscapement(float value)](#setEscapement-float-) | Trả về hoặc thiết lập văn bản trên chỉ số hoặc dưới chỉ số. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Trả về hoặc thiết lập kích thước phông chữ tối thiểu, mà ở đó kerning sẽ được bật. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Trả về hoặc thiết lập kích thước phông chữ tối thiểu, mà ở đó kerning sẽ được bật. |
| [getLanguageId()](#getLanguageId--) | Trả về hoặc thiết lập Id của ngôn ngữ kiểm tra chính tả. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Trả về hoặc thiết lập Id của ngôn ngữ kiểm tra chính tả. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Trả về hoặc thiết lập Id của ngôn ngữ thay thế. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Trả về hoặc thiết lập Id của ngôn ngữ thay thế. |
| [getSpacing()](#getSpacing--) | Trả về hoặc thiết lập mức tăng khoảng cách giữa các ký tự. |
| [setSpacing(float value)](#setSpacing-float-) | Trả về hoặc thiết lập mức tăng khoảng cách giữa các ký tự. |
| [getSpellCheck()](#getSpellCheck--) | Lấy hoặc đặt giá trị cho biết kiểm tra chính tả có được bật cho phần văn bản hay không. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Lấy hoặc đặt giá trị cho biết kiểm tra chính tả có được bật cho phần văn bản hay không. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. Chỉ đọc kiểu long.

**Trả về:**
long

### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

Trả về các thuộc tính LineFormat cho việc viền văn bản. Không áp dụng kế thừa. Chỉ đọc [ILineFormat](../../com.aspose.slides/ilineformat).

**Trả về:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Trả về các thuộc tính FillFormat của văn bản. Không áp dụng kế thừa. Chỉ đọc [IFillFormat](../../com.aspose.slides/ifillformat).

**Trả về:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Trả về các thuộc tính EffectFormat của văn bản. Không áp dụng kế thừa. Chỉ đọc [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Trả về:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

Trả về màu được dùng để làm nổi bật văn bản. Không áp dụng kế thừa. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

Trả về các thuộc tính LineFormat được dùng để viền đường gạch dưới. Không áp dụng kế thừa. Chỉ đọc [ILineFormat](../../com.aspose.slides/ilineformat).

**Trả về:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

Trả về các thuộc tính FillFormat của đường gạch dưới. Không áp dụng kế thừa. Chỉ đọc [IFillFormat](../../com.aspose.slides/ifillformat).

**Trả về:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

Xác định xem phông chữ có in đậm hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

Xác định xem phông chữ có in đậm hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

Xác định xem phông chữ có nghiêng hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

Xác định xem phông chữ có nghiêng hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

Xác định xem các số có nên bỏ qua bố cục văn bản dọc đặc trưng cho ngôn ngữ phía Đông không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

Xác định xem các số có nên bỏ qua bố cục văn bản dọc đặc trưng cho ngôn ngữ phía Đông không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

Xác định xem chiều cao của văn bản có nên được chuẩn hoá không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

Xác định xem chiều cao của văn bản có nên được chuẩn hoá không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

Xác định xem văn bản không nên được kiểm tra lỗi chính tả hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

Xác định xem văn bản không nên được kiểm tra lỗi chính tả hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

Trả về hoặc thiết lập kiểu gạch dưới của văn bản. Không áp dụng kế thừa. Đọc/ghi [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Trả về:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

Trả về hoặc thiết lập kiểu gạch dưới của văn bản. Không áp dụng kế thừa. Đọc/ghi [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

Trả về hoặc thiết lập kiểu chữ in hoa/chữ thường của văn bản. Không áp dụng kế thừa. Đọc/ghi [TextCapType](../../com.aspose.slides/textcaptype).

**Trả về:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

Trả về hoặc thiết lập kiểu chữ in hoa/chữ thường của văn bản. Không áp dụng kế thừa. Đọc/ghi [TextCapType](../../com.aspose.slides/textcaptype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

Trả về hoặc thiết lập kiểu gạch ngang của văn bản. Không áp dụng kế thừa. Đọc/ghi [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Trả về:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

Trả về hoặc thiết lập kiểu gạch ngang của văn bản. Không áp dụng kế thừa. Đọc/ghi [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

Xác định xem kiểu gạch dưới có các thuộc tính LineFormat riêng hay kế thừa từ các thuộc tính LineFormat của văn bản. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

Xác định xem kiểu gạch dưới có các thuộc tính LineFormat riêng hay kế thừa từ các thuộc tính LineFormat của văn bản. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

Xác định xem kiểu gạch dưới có các thuộc tính FillFormat riêng hay kế thừa từ các thuộc tính FillFormat của văn bản. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

Xác định xem kiểu gạch dưới có các thuộc tính FillFormat riêng hay kế thừa từ các thuộc tính FillFormat của văn bản. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

Trả về hoặc thiết lập chiều cao phông chữ của một phần. **Float.NaN** có nghĩa là chiều cao chưa xác định và sẽ kế thừa từ Master. Đọc/ghi  float .

**Trả về:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

Trả về hoặc thiết lập chiều cao phông chữ của một phần. **Float.NaN** có nghĩa là chiều cao chưa xác định và sẽ kế thừa từ Master. Đọc/ghi  float .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Trả về hoặc thiết lập thông tin phông chữ Latin. Null có nghĩa là phông chữ chưa xác định và sẽ kế thừa từ Master. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Trả về hoặc thiết lập thông tin phông chữ Latin. Null có nghĩa là phông chữ chưa xác định và sẽ kế thừa từ Master. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Trả về hoặc thiết lập thông tin phông chữ Đông Á. Null có nghĩa là phông chữ chưa xác định và sẽ kế thừa từ Master. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Trả về hoặc thiết lập thông tin phông chữ Đông Á. Null có nghĩa là phông chữ chưa xác định và sẽ kế thừa từ Master. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Trả về hoặc thiết lập thông tin phông chữ script phức tạp. Null có nghĩa là phông chữ chưa xác định và sẽ kế thừa từ Master. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Trả về hoặc thiết lập thông tin phông chữ script phức tạp. Null có nghĩa là phông chữ chưa xác định và sẽ kế thừa từ Master. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

Trả về hoặc thiết lập thông tin phông chữ ký hiệu. Null có nghĩa là phông chữ chưa xác định và sẽ kế thừa từ Master. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

Trả về hoặc thiết lập thông tin phông chữ ký hiệu. Null có nghĩa là phông chữ chưa xác định và sẽ kế thừa từ Master. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

Trả về hoặc thiết lập văn bản trên chỉ số hoặc dưới chỉ số. Giá trị từ -100% (dưới chỉ số) đến 100% (trên chỉ số). **Float.NaN** có nghĩa là giá trị chưa xác định và sẽ kế thừa từ Master. Đọc/ghi  float .

**Trả về:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

Trả về hoặc thiết lập văn bản trên chỉ số hoặc dưới chỉ số. Giá trị từ -100% (dưới chỉ số) đến 100% (trên chỉ số). **Float.NaN** có nghĩa là giá trị chưa xác định và sẽ kế thừa từ Master. Đọc/ghi  float .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

Trả về hoặc thiết lập kích thước phông chữ tối thiểu, mà ở đó kerning sẽ được bật. **Float.NaN** có nghĩa là giá trị chưa xác định và sẽ kế thừa từ Master. Đọc/ghi  float .

**Trả về:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

Trả về hoặc thiết lập kích thước phông chữ tối thiểu, mà ở đó kerning sẽ được bật. **Float.NaN** có nghĩa là giá trị chưa xác định và sẽ kế thừa từ Master. Đọc/ghi  float .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

Trả về hoặc thiết lập Id của ngôn ngữ kiểm tra chính tả. Dùng để kiểm tra chính tả và ngữ pháp. Đọc/ghi String.

**Trả về:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

Trả về hoặc thiết lập Id của ngôn ngữ kiểm tra chính tả. Dùng để kiểm tra chính tả và ngữ pháp. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

Trả về hoặc thiết lập Id của ngôn ngữ thay thế. Đọc/ghi String.

**Trả về:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

Trả về hoặc thiết lập Id của ngôn ngữ thay thế. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

Trả về hoặc thiết lập mức tăng khoảng cách giữa các ký tự. **Float.NaN** có nghĩa là giá trị chưa xác định và sẽ kế thừa từ Master. Đọc/ghi  float .

**Trả về:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

Trả về hoặc thiết lập mức tăng khoảng cách giữa các ký tự. **Float.NaN** có nghĩa là giá trị chưa xác định và sẽ kế thừa từ Master. Đọc/ghi  float .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

Lấy hoặc đặt giá trị cho biết kiểm tra chính tả có được bật cho phần văn bản hay không. Khi thuộc tính này được đặt thành false, việc kiểm tra chính tả cho các phần tử văn bản sẽ bị vô hiệu hoá. Khi đặt thành true, kiểm tra chính tả sẽ được cho phép. Giá trị mặc định là false.

**Trả về:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public final void setSpellCheck(boolean value)
```

Lấy hoặc đặt giá trị cho biết kiểm tra chính tả có được bật cho phần văn bản hay không. Khi thuộc tính này được đặt thành false, việc kiểm tra chính tả cho các phần tử văn bản sẽ bị vô hiệu hoá. Khi đặt thành true, kiểm tra chính tả sẽ được cho phép. Giá trị mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Truy cập phần văn bản đầu tiên bên trong hình dạng đầu tiên trên slide đầu tiên
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Bật kiểm tra chính tả cho phần văn bản này
>      portion.getPortionFormat().setSpellCheck(true);
>      // Lưu bản trình chiếu đã sửa đổi
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
boolean

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Truy cập phần văn bản đầu tiên bên trong hình dạng đầu tiên trên slide đầu tiên
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Bật kiểm tra chính tả cho phần văn bản này
>      portion.getPortionFormat().setSpellCheck(true);
>      // Lưu bản trình chiếu đã sửa đổi
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |