---
title: IBasePortionFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Lớp này chứa các thuộc tính định dạng phần văn bản.
type: docs
url: /vi/com.aspose.slides/ibaseportionformat/
---```
public interface IBasePortionFormat
```

Lớp này chứa các thuộc tính định dạng phần văn bản. Khác với [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), tất cả các thuộc tính của lớp này đều có thể ghi.

--------------------

Lớp này được sử dụng để trả về và thao tác các thuộc tính định dạng phần văn bản được xác định cho phần cụ thể. Điều này có nghĩa là không có kế thừa được áp dụng khi lấy giá trị, vì vậy trong phần lớn các trường hợp bạn sẽ nhận được các giá trị có nghĩa là “undefined”.

Để lấy các giá trị tham số định dạng hiệu quả bao gồm cả được kế thừa, bạn cần sử dụng phương thức [IPortionFormat.getEffective](../../com.aspose.slides/iportionformat\#getEffective) trả về một thể hiện [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Trả về các thuộc tính LineFormat cho việc viền văn bản. |
| [getFillFormat()](#getFillFormat--) | Trả về các thuộc tính FillFormat của văn bản. |
| [getEffectFormat()](#getEffectFormat--) | Trả về các thuộc tính EffectFormat của văn bản. |
| [getHighlightColor()](#getHighlightColor--) | Trả về màu được sử dụng để làm nổi bật văn bản. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | Trả về các thuộc tính LineFormat được sử dụng để viền đường gạch dưới. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | Trả về các thuộc tính FillFormat của đường gạch dưới. |
| [getFontBold()](#getFontBold--) | Xác định xem phông chữ có in đậm hay không. |
| [setFontBold(byte value)](#setFontBold-byte-) | Xác định xem phông chữ có in đậm hay không. |
| [getFontItalic()](#getFontItalic--) | Xác định xem phông chữ có in nghiêng hay không. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | Xác định xem phông chữ có in nghiêng hay không. |
| [getKumimoji()](#getKumimoji--) | Xác định xem các số có nên bỏ qua bố cục văn bản dọc đặc thù cho ngôn ngữ phía Đông hay không. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | Xác định xem các số có nên bỏ qua bố cục văn bản dọc đặc thù cho ngôn ngữ phía Đông hay không. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Xác định xem chiều cao của văn bản có nên được chuẩn hoá hay không. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | Xác định xem chiều cao của văn bản có nên được chuẩn hoá hay không. |
| [getProofDisabled()](#getProofDisabled--) | Xác định xem văn bản không nên được kiểm tra chính tả hay không. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | Xác định xem văn bản không nên được kiểm tra chính tả hay không. |
| [getFontUnderline()](#getFontUnderline--) | Trả về hoặc đặt kiểu gạch dưới của văn bản. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | Trả về hoặc đặt kiểu gạch dưới của văn bản. |
| [getTextCapType()](#getTextCapType--) | Trả về hoặc đặt kiểu viết hoa của văn bản. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | Trả về hoặc đặt kiểu viết hoa của văn bản. |
| [getStrikethroughType()](#getStrikethroughType--) | Trả về hoặc đặt kiểu gạch ngang của văn bản. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | Trả về hoặc đặt kiểu gạch ngang của văn bản. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Xác định xem kiểu gạch dưới có các thuộc tính LineFormat riêng hay kế thừa từ các thuộc tính LineFormat của văn bản. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | Xác định xem kiểu gạch dưới có các thuộc tính LineFormat riêng hay kế thừa từ các thuộc tính LineFormat của văn bản. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Xác định xem kiểu gạch dưới có các thuộc tính FillFormat riêng hay kế thừa từ các thuộc tính FillFormat của văn bản. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | Xác định xem kiểu gạch dưới có các thuộc tính FillFormat riêng hay kế thừa từ các thuộc tính FillFormat của văn bản. |
| [getFontHeight()](#getFontHeight--) | Trả về hoặc đặt chiều cao phông chữ của một phần. |
| [setFontHeight(float value)](#setFontHeight-float-) | Trả về hoặc đặt chiều cao phông chữ của một phần. |
| [getLatinFont()](#getLatinFont--) | Trả về hoặc đặt thông tin phông chữ Latin. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Trả về hoặc đặt thông tin phông chữ Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Trả về hoặc đặt thông tin phông chữ Đông Á. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Trả về hoặc đặt thông tin phông chữ Đông Á. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Trả về hoặc đặt thông tin phông chữ kịch bản phức tạp. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Trả về hoặc đặt thông tin phông chữ kịch bản phức tạp. |
| [getSymbolFont()](#getSymbolFont--) | Trả về hoặc đặt thông tin phông chữ ký hiệu. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | Trả về hoặc đặt thông tin phông chữ ký hiệu. |
| [getEscapement()](#getEscapement--) | Trả về hoặc đặt văn bản chỉ số trên hoặc chỉ số dưới. |
| [setEscapement(float value)](#setEscapement-float-) | Trả về hoặc đặt văn bản chỉ số trên hoặc chỉ số dưới. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Trả về hoặc đặt kích thước phông chữ tối thiểu, mà ở đó kerning nên được bật. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | Trả về hoặc đặt kích thước phông chữ tối thiểu, mà ở đó kerning nên được bật. |
| [getLanguageId()](#getLanguageId--) | Trả về hoặc đặt Id của ngôn ngữ kiểm tra chính tả. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | Trả về hoặc đặt Id của ngôn ngữ kiểm tra chính tả. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Trả về hoặc đặt Id của ngôn ngữ thay thế. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | Trả về hoặc đặt Id của ngôn ngữ thay thế. |
| [getSpacing()](#getSpacing--) | Trả về hoặc đặt mức tăng khoảng cách giữa các ký tự. |
| [setSpacing(float value)](#setSpacing-float-) | Trả về hoặc đặt mức tăng khoảng cách giữa các ký tự. |
| [getSpellCheck()](#getSpellCheck--) | Lấy hoặc đặt giá trị cho biết có bật kiểm tra chính tả cho phần văn bản hay không. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | Lấy hoặc đặt giá trị cho biết có bật kiểm tra chính tả cho phần văn bản hay không. |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Trả về các thuộc tính LineFormat cho việc viền văn bản. Không áp dụng kế thừa. Chỉ đọc [ILineFormat](../../com.aspose.slides/ilineformat).

**Trả về:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Trả về các thuộc tính FillFormat của văn bản. Không áp dụng kế thừa. Chỉ đọc [IFillFormat](../../com.aspose.slides/ifillformat).

**Trả về:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Trả về các thuộc tính EffectFormat của văn bản. Không áp dụng kế thừa. Chỉ đọc [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Trả về:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getHighlightColor() {#getHighlightColor--}
```
public abstract IColorFormat getHighlightColor()
```

Trả về màu được sử dụng để làm nổi bật văn bản. Không áp dụng kế thừa. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormat getUnderlineLineFormat()
```

Trả về các thuộc tính LineFormat được sử dụng để viền đường gạch dưới. Không áp dụng kế thừa. Chỉ đọc [ILineFormat](../../com.aspose.slides/ilineformat).

**Trả về:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormat getUnderlineFillFormat()
```

Trả về các thuộc tính FillFormat của đường gạch dưới. Không áp dụng kế thừa. Chỉ đọc [IFillFormat](../../com.aspose.slides/ifillformat).

**Trả về:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getFontBold() {#getFontBold--}
```
public abstract byte getFontBold()
```

Xác định xem phông chữ có in đậm hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setFontBold(byte value) {#setFontBold-byte-}
```
public abstract void setFontBold(byte value)
```

Xác định xem phông chữ có in đậm hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getFontItalic() {#getFontItalic--}
```
public abstract byte getFontItalic()
```

Xác định xem phông chữ có in nghiêng hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setFontItalic(byte value) {#setFontItalic-byte-}
```
public abstract void setFontItalic(byte value)
```

Xác định xem phông chữ có in nghiêng hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getKumimoji() {#getKumimoji--}
```
public abstract byte getKumimoji()
```

Xác định xem các số có nên bỏ qua bố cục văn bản dọc đặc thù cho ngôn ngữ phía Đông hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setKumimoji(byte value) {#setKumimoji-byte-}
```
public abstract void setKumimoji(byte value)
```

Xác định xem các số có nên bỏ qua bố cục văn bản dọc đặc thù cho ngôn ngữ phía Đông hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract byte getNormaliseHeight()
```

Xác định xem chiều cao của văn bản có nên được chuẩn hoá hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public abstract void setNormaliseHeight(byte value)
```

Xác định xem chiều cao của văn bản có nên được chuẩn hoá hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getProofDisabled() {#getProofDisabled--}
```
public abstract byte getProofDisabled()
```

Xác định xem văn bản không nên được kiểm tra chính tả hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public abstract void setProofDisabled(byte value)
```

Xác định xem văn bản không nên được kiểm tra chính tả hay không. Không áp dụng kế thừa. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Trả về hoặc đặt kiểu gạch dưới của văn bản. Không áp dụng kế thừa. Đọc/ghi [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Trả về:**
byte

### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public abstract void setFontUnderline(byte value)
```

Trả về hoặc đặt kiểu gạch dưới của văn bản. Không áp dụng kế thừa. Đọc/ghi [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Trả về hoặc đặt kiểu viết hoa của văn bản. Không áp dụng kế thừa. Đọc/ghi [TextCapType](../../com.aspose.slides/textcaptype).

**Trả về:**
byte

### setTextCapType(byte value) {#setTextCapType-byte-}
```
public abstract void setTextCapType(byte value)
```

Trả về hoặc đặt kiểu viết hoa của văn bản. Không áp dụng kế thừa. Đọc/ghi [TextCapType](../../com.aspose.slides/textcaptype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Trả về hoặc đặt kiểu gạch ngang của văn bản. Không áp dụng kế thừa. Đọc/ghi [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Trả về:**
byte

### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public abstract void setStrikethroughType(byte value)
```

Trả về hoặc đặt kiểu gạch ngang của văn bản. Không áp dụng kế thừa. Đọc/ghi [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract byte isHardUnderlineLine()
```

Xác định xem kiểu gạch dưới có các thuộc tính LineFormat riêng hay kế thừa từ các thuộc tính LineFormat của văn bản. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public abstract void setHardUnderlineLine(byte value)
```

Xác định xem kiểu gạch dưới có các thuộc tính LineFormat riêng hay kế thừa từ các thuộc tính LineFormat của văn bản. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract byte isHardUnderlineFill()
```

Xác định xem kiểu gạch dưới có các thuộc tính FillFormat riêng hay kế thừa từ các thuộc tính FillFormat của văn bản. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public abstract void setHardUnderlineFill(byte value)
```

Xác định xem kiểu gạch dưới có các thuộc tính FillFormat riêng hay kế thừa từ các thuộc tính FillFormat của văn bản. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Trả về hoặc đặt chiều cao phông chữ của một phần. **Float.NaN** có nghĩa là chiều cao không xác định và nên được kế thừa từ Master. Đọc/ghi float.

**Trả về:**
float

### setFontHeight(float value) {#setFontHeight-float-}
```
public abstract void setFontHeight(float value)
```

Trả về hoặc đặt chiều cao phông chữ của một phần. **Float.NaN** có nghĩa là chiều cao không xác định và nên được kế thừa từ Master. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Trả về hoặc đặt thông tin phông chữ Latin. Null có nghĩa là phông chữ không xác định và nên được kế thừa từ Master. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Trả về hoặc đặt thông tin phông chữ Latin. Null có nghĩa là phông chữ không xác định và nên được kế thừa từ Master. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Trả về hoặc đặt thông tin phông chữ Đông Á. Null có nghĩa là phông chữ không xác định và nên được kế thừa từ Master. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Trả về hoặc đặt thông tin phông chữ Đông Á. Null có nghĩa là phông chữ không xác định và nên được kế thừa từ Master. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Trả về hoặc đặt thông tin phông chữ kịch bản phức tạp. Null có nghĩa là phông chữ không xác định và nên được kế thừa từ Master. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Trả về hoặc đặt thông tin phông chữ kịch bản phức tạp. Null có nghĩa là phông chữ không xác định và nên được kế thừa từ Master. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Trả về hoặc đặt thông tin phông chữ ký hiệu. Null có nghĩa là phông chữ không xác định và nên được kế thừa từ Master. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)

### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public abstract void setSymbolFont(IFontData value)
```

Trả về hoặc đặt thông tin phông chữ ký hiệu. Null có nghĩa là phông chữ không xác định và nên được kế thừa từ Master. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Trả về hoặc đặt văn bản chỉ số trên hoặc chỉ số dưới. Giá trị từ -100% (chỉ số dưới) tới 100% (chỉ số trên). **Float.NaN** có nghĩa là giá trị không xác định và nên được kế thừa từ Master. Đọc/ghi float.

**Trả về:**
float

### setEscapement(float value) {#setEscapement-float-}
```
public abstract void setEscapement(float value)
```

Trả về hoặc đặt văn bản chỉ số trên hoặc chỉ số dưới. Giá trị từ -100% (chỉ số dưới) tới 100% (chỉ số trên). **Float.NaN** có nghĩa là giá trị không xác định và nên được kế thừa từ Master. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Trả về hoặc đặt kích thước phông chữ tối thiểu, mà ở đó kerning nên được bật. **Float.NaN** có nghĩa là giá trị không xác định và nên được kế thừa từ Master. Đọc/ghi float.

**Trả về:**
float

### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public abstract void setKerningMinimalSize(float value)
```

Trả về hoặc đặt kích thước phông chữ tối thiểu, mà ở đó kerning nên được bật. **Float.NaN** có nghĩa là giá trị không xác định và nên được kế thừa từ Master. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Trả về hoặc đặt Id của ngôn ngữ kiểm tra chính tả. Được sử dụng để kiểm tra chính tả và ngữ pháp. Đọc/ghi String.

**Trả về:**
java.lang.String

### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public abstract void setLanguageId(String value)
```

Trả về hoặc đặt Id của ngôn ngữ kiểm tra chính tả. Được sử dụng để kiểm tra chính tả và ngữ pháp. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Trả về hoặc đặt Id của ngôn ngữ thay thế. Đọc/ghi String.

**Trả về:**
java.lang.String

### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public abstract void setAlternativeLanguageId(String value)
```

Trả về hoặc đặt Id của ngôn ngữ thay thế. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Trả về hoặc đặt mức tăng khoảng cách giữa các ký tự. **Float.NaN** có nghĩa là giá trị không xác định và nên được kế thừa từ Master. Đọc/ghi float.

**Trả về:**
float

### setSpacing(float value) {#setSpacing-float-}
```
public abstract void setSpacing(float value)
```

Trả về hoặc đặt mức tăng khoảng cách giữa các ký tự. **Float.NaN** có nghĩa là giá trị không xác định và nên được kế thừa từ Master. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getSpellCheck() {#getSpellCheck--}
```
public abstract boolean getSpellCheck()
```

Lấy hoặc đặt giá trị cho biết có bật kiểm tra chính tả cho phần văn bản hay không. Khi thuộc tính này được đặt thành false, việc kiểm tra chính tả cho các yếu tố văn bản sẽ bị vô hiệu hoá. Khi đặt thành true, kiểm tra chính tả được cho phép. Giá trị mặc định là false.

--------------------

> ```
> Ví dụ tiếp theo minh họa cách bật cờ SpellCheck trước khi lưu bản trình bày:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Truy cập phần văn bản đầu tiên bên trong hình dạng đầu tiên trên slide đầu tiên
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Bật kiểm tra chính tả cho phần văn bản này
>      portion.getPortionFormat().setSpellCheck(true);
>      // Lưu bản trình bày đã chỉnh sửa
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
boolean

### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public abstract void setSpellCheck(boolean value)
```

Lấy hoặc đặt giá trị cho biết có bật kiểm tra chính tả cho phần văn bản hay không. Khi thuộc tính này được đặt thành false, việc kiểm tra chính tả cho các yếu tố văn bản sẽ bị vô hiệu hoá. Khi đặt thành true, kiểm tra chính tả được cho phép. Giá trị mặc định là false.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // Access the first portion of text inside the first shape on the first slide
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Enable spell checking for this text portion
>      portion.getPortionFormat().setSpellCheck(true);
>      // Save the modified presentation
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |