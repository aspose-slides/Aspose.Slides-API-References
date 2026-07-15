---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides cho Android thông qua Java API Reference
description: Giao diện cơ sở cho các đối tượng bất biến chứa các thuộc tính định dạng phần văn bản hiệu chỉnh.
type: docs
url: /vi/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

Giao diện cơ sở cho các đối tượng bất biến chứa các thuộc tính định dạng phần văn bản hiệu chỉnh.
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
| [getFontItalic()](#getFontItalic--) | Xác định xem phông chữ có in nghiêng hay không. |
| [getKumimoji()](#getKumimoji--) | Xác định xem các số có nên bỏ qua bố cục văn bản dọc đặc thù cho ngôn ngữ phía Đông hay không. |
| [getNormaliseHeight()](#getNormaliseHeight--) | Xác định xem chiều cao của văn bản có nên được chuẩn hoá hay không. |
| [getProofDisabled()](#getProofDisabled--) | Xác định xem văn bản không nên được kiểm tra lỗi chính tả hay không. |
| [getFontUnderline()](#getFontUnderline--) | Trả về loại gạch dưới của văn bản. |
| [getTextCapType()](#getTextCapType--) | Trả về loại viết hoa của văn bản. |
| [getStrikethroughType()](#getStrikethroughType--) | Trả về loại gạch ngang của văn bản. |
| [getSmartTagClean()](#getSmartTagClean--) | Xác định xem thẻ thông minh có nên được làm sạch hay không. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | Xác định xem kiểu gạch dưới có các thuộc tính LineFormat riêng hay kế thừa từ các thuộc tính LineFormat của văn bản. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | Xác định xem kiểu gạch dưới có các thuộc tính FillFormat riêng hay kế thừa từ các thuộc tính FillFormat của văn bản. |
| [getFontHeight()](#getFontHeight--) | Trả về chiều cao phông chữ của phần văn bản, tính bằng point. |
| [getLatinFont()](#getLatinFont--) | Trả về thông tin phông chữ Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Trả về thông tin phông chữ Đông Á. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Trả về thông tin phông chữ kịch bản phức tạp. |
| [getSymbolFont()](#getSymbolFont--) | Trả về thông tin phông chữ ký hiệu. |
| [getEscapement()](#getEscapement--) | Trả về văn bản dạng chỉ số trên hoặc chỉ số dưới. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | Trả về kích thước phông chữ tối thiểu, mà ở đó kerning sẽ được bật. |
| [getLanguageId()](#getLanguageId--) | Trả về Id của một ngôn ngữ. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | Trả về Id của một ngôn ngữ thay thế. |
| [getSpacing()](#getSpacing--) | Trả về mức tăng khoảng cách giữa các ký tự, tính bằng point. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```

Trả về các thuộc tính LineFormat cho việc viền văn bản. Chỉ đọc [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Trả về:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

Trả về các thuộc tính FillFormat của văn bản. Chỉ đọc [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Trả về:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

Trả về các thuộc tính EffectFormat của văn bản. Chỉ đọc [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Trả về:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Integer getHighlightColor()
```

Trả về màu được sử dụng để làm nổi bật văn bản. Chỉ đọc java.lang.Integer.

**Trả về:**
java.lang.Integer
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

Trả về các thuộc tính LineFormat được sử dụng để viền đường gạch dưới. Chỉ đọc [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**Trả về:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```

Trả về các thuộc tính FillFormat của đường gạch dưới. Chỉ đọc [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Trả về:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```

Xác định xem phông chữ có in đậm hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```

Xác định xem phông chữ có in nghiêng hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```

Xác định xem các số có nên bỏ qua bố cục văn bản dọc đặc thù cho ngôn ngữ phía Đông hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```

Xác định xem chiều cao của văn bản có nên được chuẩn hoá hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```

Xác định xem văn bản không nên được kiểm tra lỗi chính tả hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

Trả về loại gạch dưới của văn bản. Chỉ đọc [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**Trả về:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

Trả về loại viết hoa của văn bản. Chỉ đọc [TextCapType](../../com.aspose.slides/textcaptype).

**Trả về:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

Trả về loại gạch ngang của văn bản. Chỉ đọc [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**Trả về:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Xác định xem thẻ thông minh có nên được làm sạch hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

Xác định xem kiểu gạch dưới có các thuộc tính LineFormat riêng hay kế thừa từ các thuộc tính LineFormat của văn bản. Chỉ đọc boolean.

**Trả về:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

Xác định xem kiểu gạch dưới có các thuộc tính FillFormat riêng hay kế thừa từ các thuộc tính FillFormat của văn bản. Chỉ đọc boolean.

**Trả về:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

Trả về chiều cao phông chữ của phần văn bản, tính bằng point. Chỉ đọc float.

**Trả về:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Trả về thông tin phông chữ Latin. Chỉ đọc [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Trả về thông tin phông chữ Đông Á. Chỉ đọc [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Trả về thông tin phông chữ kịch bản phức tạp. Chỉ đọc [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

Trả về thông tin phông chữ ký hiệu. Chỉ đọc [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

Trả về văn bản dạng chỉ số trên hoặc chỉ số dưới. Giá trị từ -100 % (chỉ số dưới) đến 100 % (chỉ số trên). Chỉ đọc float.

**Trả về:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

Trả về kích thước phông chữ tối thiểu, mà ở đó kerning sẽ được bật. Chỉ đọc float.

**Trả về:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

Trả về Id của một ngôn ngữ. Chỉ đọc String.

**Trả về:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

Trả về Id của một ngôn ngữ thay thế. Chỉ đọc String.

**Trả về:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

Trả về mức tăng khoảng cách giữa các ký tự, tính bằng point. Chỉ đọc float.

**Trả về:**
float