---
title: BasePortionFormat
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 공통 텍스트 부분 서식 속성.
type: docs
url: /ko/com.aspose.slides/baseportionformat/
---
**상속:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**구현된 모든 인터페이스:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat)
```
public abstract class BasePortionFormat extends PVIObject implements IBasePortionFormat
```

공통 텍스트 부분 서식 속성.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLineFormat()](#getLineFormat--) | 텍스트 외곽선에 대한 LineFormat 속성을 반환합니다. |
| [getFillFormat()](#getFillFormat--) | 텍스트 FillFormat 속성을 반환합니다. |
| [getEffectFormat()](#getEffectFormat--) | 텍스트 EffectFormat 속성을 반환합니다. |
| [getHighlightColor()](#getHighlightColor--) | 텍스트를 강조 표시하는 데 사용되는 색상을 반환합니다. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | 밑줄 선을 외곽선 처리하는 데 사용되는 LineFormat 속성을 반환합니다. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | 밑줄 선 FillFormat 속성을 반환합니다. |
| [getFontBold()](#getFontBold--) | 글꼴이 굵게인지 여부를 결정합니다. |
| [setFontBold(byte value)](#setFontBold-byte-) | 글꼴이 굵게인지 여부를 결정합니다. |
| [getFontItalic()](#getFontItalic--) | 글꼴이 이탤릭인지 여부를 결정합니다. |
| [setFontItalic(byte value)](#setFontItalic-byte-) | 글꼴이 이탤릭인지 여부를 결정합니다. |
| [getKumimoji()](#getKumimoji--) | 숫자가 동아시아 언어별 세로 텍스트 레이아웃을 무시해야 하는지 여부를 결정합니다. |
| [setKumimoji(byte value)](#setKumimoji-byte-) | 숫자가 동아시아 언어별 세로 텍스트 레이아웃을 무시해야 하는지 여부를 결정합니다. |
| [getNormaliseHeight()](#getNormaliseHeight--) | 텍스트 높이를 정규화해야 하는지 여부를 결정합니다. |
| [setNormaliseHeight(byte value)](#setNormaliseHeight-byte-) | 텍스트 높이를 정규화해야 하는지 여부를 결정합니다. |
| [getProofDisabled()](#getProofDisabled--) | 텍스트에 교정을 적용하지 않아야 하는지 여부를 결정합니다. |
| [setProofDisabled(byte value)](#setProofDisabled-byte-) | 텍스트에 교정을 적용하지 않아야 하는지 여부를 결정합니다. |
| [getFontUnderline()](#getFontUnderline--) | 텍스트 밑줄 유형을 반환하거나 설정합니다. |
| [setFontUnderline(byte value)](#setFontUnderline-byte-) | 텍스트 밑줄 유형을 반환하거나 설정합니다. |
| [getTextCapType()](#getTextCapType--) | 텍스트 대소문자 변환 유형을 반환하거나 설정합니다. |
| [setTextCapType(byte value)](#setTextCapType-byte-) | 텍스트 대소문자 변환 유형을 반환하거나 설정합니다. |
| [getStrikethroughType()](#getStrikethroughType--) | 텍스트 취소선 유형을 반환하거나 설정합니다. |
| [setStrikethroughType(byte value)](#setStrikethroughType-byte-) | 텍스트 취소선 유형을 반환하거나 설정합니다. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | 밑줄 스타일이 자체 LineFormat 속성을 가지는지 또는 텍스트의 LineFormat 속성으로부터 상속받는지 여부를 결정합니다. |
| [setHardUnderlineLine(byte value)](#setHardUnderlineLine-byte-) | 밑줄 스타일이 자체 LineFormat 속성을 가지는지 또는 텍스트의 LineFormat 속성으로부터 상속받는지 여부를 결정합니다. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | 밑줄 스타일이 자체 FillFormat 속성을 가지는지 또는 텍스트의 FillFormat 속성으로부터 상속받는지 여부를 결정합니다. |
| [setHardUnderlineFill(byte value)](#setHardUnderlineFill-byte-) | 밑줄 스타일이 자체 FillFormat 속성을 가지는지 또는 텍스트의 FillFormat 속성으로부터 상속받는지 여부를 결정합니다. |
| [getFontHeight()](#getFontHeight--) | 텍스트 일부의 글꼴 높이를 반환하거나 설정합니다. |
| [setFontHeight(float value)](#setFontHeight-float-) | 텍스트 일부의 글꼴 높이를 반환하거나 설정합니다. |
| [getLatinFont()](#getLatinFont--) | 라틴 글꼴 정보를 반환하거나 설정합니다. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | 라틴 글꼴 정보를 반환하거나 설정합니다. |
| [getEastAsianFont()](#getEastAsianFont--) | 동아시아 글꼴 정보를 반환하거나 설정합니다. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | 동아시아 글꼴 정보를 반환하거나 설정합니다. |
| [getComplexScriptFont()](#getComplexScriptFont--) | 복합 스크립트 글꼴 정보를 반환하거나 설정합니다. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | 복합 스크립트 글꼴 정보를 반환하거나 설정합니다. |
| [getSymbolFont()](#getSymbolFont--) | 기호 글꼴 정보를 반환하거나 설정합니다. |
| [setSymbolFont(IFontData value)](#setSymbolFont-com.aspose.slides.IFontData-) | 기호 글꼴 정보를 반환하거나 설정합니다. |
| [getEscapement()](#getEscapement--) | 위첨자 또는 아래첨자 텍스트를 반환하거나 설정합니다. |
| [setEscapement(float value)](#setEscapement-float-) | 위첨자 또는 아래첨자 텍스트를 반환하거나 설정합니다. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | 커닝을 활성화해야 하는 최소 글꼴 크기를 반환하거나 설정합니다. |
| [setKerningMinimalSize(float value)](#setKerningMinimalSize-float-) | 커닝을 활성화해야 하는 최소 글꼴 크기를 반환하거나 설정합니다. |
| [getLanguageId()](#getLanguageId--) | 교정 언어의 Id를 반환하거나 설정합니다. |
| [setLanguageId(String value)](#setLanguageId-java.lang.String-) | 교정 언어의 Id를 반환하거나 설정합니다. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | 대체 언어의 Id를 반환하거나 설정합니다. |
| [setAlternativeLanguageId(String value)](#setAlternativeLanguageId-java.lang.String-) | 대체 언어의 Id를 반환하거나 설정합니다. |
| [getSpacing()](#getSpacing--) | 문자 간 간격 증가값을 반환하거나 설정합니다. |
| [setSpacing(float value)](#setSpacing-float-) | 문자 간 간격 증가값을 반환하거나 설정합니다. |
| [getSpellCheck()](#getSpellCheck--) | 텍스트 일부에 대해 맞춤법 검사가 활성화되어 있는지 여부를 가져오거나 설정합니다. |
| [setSpellCheck(boolean value)](#setSpellCheck-boolean-) | 텍스트 일부에 대해 맞춤법 검사가 활성화되어 있는지 여부를 가져오거나 설정합니다. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환:**
long
### getLineFormat() {#getLineFormat--}
```
public final ILineFormat getLineFormat()
```

텍스트 외곽선에 대한 LineFormat 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [ILineFormat](../../com.aspose.slides/ilineformat).

**반환:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

텍스트 FillFormat 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IFillFormat](../../com.aspose.slides/ifillformat).

**반환:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

텍스트 EffectFormat 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IEffectFormat](../../com.aspose.slides/ieffectformat).

**반환:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getHighlightColor() {#getHighlightColor--}
```
public final IColorFormat getHighlightColor()
```

텍스트를 강조 표시하는 데 사용되는 색상을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public final ILineFormat getUnderlineLineFormat()
```

밑줄 선을 외곽선 처리하는 데 사용되는 LineFormat 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [ILineFormat](../../com.aspose.slides/ilineformat).

**반환:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public final IFillFormat getUnderlineFillFormat()
```

밑줄 선 FillFormat 속성을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IFillFormat](../../com.aspose.slides/ifillformat).

**반환:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getFontBold() {#getFontBold--}
```
public final byte getFontBold()
```

글꼴이 굵게인지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**
byte
### setFontBold(byte value) {#setFontBold-byte-}
```
public final void setFontBold(byte value)
```

글꼴이 굵게인지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getFontItalic() {#getFontItalic--}
```
public final byte getFontItalic()
```

글꼴이 이탤릭인지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**
byte
### setFontItalic(byte value) {#setFontItalic-byte-}
```
public final void setFontItalic(byte value)
```

글꼴이 이탤릭인지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getKumimoji() {#getKumimoji--}
```
public final byte getKumimoji()
```

숫자가 동아시아 언어별 세로 텍스트 레이아웃을 무시해야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**
byte
### setKumimoji(byte value) {#setKumimoji-byte-}
```
public final void setKumimoji(byte value)
```

숫자가 동아시아 언어별 세로 텍스트 레이아웃을 무시해야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getNormaliseHeight() {#getNormaliseHeight--}
```
public final byte getNormaliseHeight()
```

텍스트 높이를 정규화해야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**
byte
### setNormaliseHeight(byte value) {#setNormaliseHeight-byte-}
```
public final void setNormaliseHeight(byte value)
```

텍스트 높이를 정규화해야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getProofDisabled() {#getProofDisabled--}
```
public final byte getProofDisabled()
```

텍스트에 교정을 적용하지 않아야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**
byte
### setProofDisabled(byte value) {#setProofDisabled-byte-}
```
public final void setProofDisabled(byte value)
```

텍스트에 교정을 적용하지 않아야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getFontUnderline() {#getFontUnderline--}
```
public final byte getFontUnderline()
```

텍스트 밑줄 유형을 반환하거나 설정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**반환:**
byte
### setFontUnderline(byte value) {#setFontUnderline-byte-}
```
public final void setFontUnderline(byte value)
```

텍스트 밑줄 유형을 반환하거나 설정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getTextCapType() {#getTextCapType--}
```
public final byte getTextCapType()
```

텍스트 대소문자 변환 유형을 반환하거나 설정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [TextCapType](../../com.aspose.slides/textcaptype).

**반환:**
byte
### setTextCapType(byte value) {#setTextCapType-byte-}
```
public final void setTextCapType(byte value)
```

텍스트 대소문자 변환 유형을 반환하거나 설정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [TextCapType](../../com.aspose.slides/textcaptype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getStrikethroughType() {#getStrikethroughType--}
```
public final byte getStrikethroughType()
```

텍스트 취소선 유형을 반환하거나 설정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**반환:**
byte
### setStrikethroughType(byte value) {#setStrikethroughType-byte-}
```
public final void setStrikethroughType(byte value)
```

텍스트 취소선 유형을 반환하거나 설정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public final byte isHardUnderlineLine()
```

밑줄 스타일이 자체 LineFormat 속성을 가지는지 또는 텍스트의 LineFormat 속성으로부터 상속받는지 여부를 결정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**
byte
### setHardUnderlineLine(byte value) {#setHardUnderlineLine-byte-}
```
public final void setHardUnderlineLine(byte value)
```

밑줄 스타일이 자체 LineFormat 속성을 가지는지 또는 텍스트의 LineFormat 속성으로부터 상속받는지 여부를 결정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public final byte isHardUnderlineFill()
```

밑줄 스타일이 자체 FillFormat 속성을 가지는지 또는 텍스트의 FillFormat 속성으로부터 상속받는지 여부를 결정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**
byte
### setHardUnderlineFill(byte value) {#setHardUnderlineFill-byte-}
```
public final void setHardUnderlineFill(byte value)
```

밑줄 스타일이 자체 FillFormat 속성을 가지는지 또는 텍스트의 FillFormat 속성으로부터 상속받는지 여부를 결정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getFontHeight() {#getFontHeight--}
```
public final float getFontHeight()
```

텍스트 일부의 글꼴 높이를 반환하거나 설정합니다. **Float.NaN**는 높이가 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기  float .

**반환:**
float
### setFontHeight(float value) {#setFontHeight-float-}
```
public final void setFontHeight(float value)
```

텍스트 일부의 글꼴 높이를 반환하거나 설정합니다. **Float.NaN**는 높이가 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기  float .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |
### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

라틴 글꼴 정보를 반환하거나 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**반환:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

라틴 글꼴 정보를 반환하거나 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

동아시아 글꼴 정보를 반환하거나 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**반환:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

동아시아 글꼴 정보를 반환하거나 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

복합 스크립트 글꼴 정보를 반환하거나 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**반환:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

복합 스크립트 글꼴 정보를 반환하거나 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getSymbolFont() {#getSymbolFont--}
```
public final IFontData getSymbolFont()
```

기호 글꼴 정보를 반환하거나 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**반환:**
[IFontData](../../com.aspose.slides/ifontdata)
### setSymbolFont(IFontData value) {#setSymbolFont-com.aspose.slides.IFontData-}
```
public final void setSymbolFont(IFontData value)
```

기호 글꼴 정보를 반환하거나 설정합니다. Null은 글꼴이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEscapement() {#getEscapement--}
```
public final float getEscapement()
```

위첨자 또는 아래첨자 텍스트를 반환하거나 설정합니다. -100% (아래첨자)에서 100% (위첨자)까지의 값입니다. **Float.NaN**는 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기  float .

**반환:**
float
### setEscapement(float value) {#setEscapement-float-}
```
public final void setEscapement(float value)
```

위첨자 또는 아래첨자 텍스트를 반환하거나 설정합니다. -100% (아래첨자)에서 100% (위첨자)까지의 값입니다. **Float.NaN**는 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기  float .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public final float getKerningMinimalSize()
```

커닝을 활성화해야 하는 최소 글꼴 크기를 반환하거나 설정합니다. **Float.NaN**는 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기  float .

**반환:**
float
### setKerningMinimalSize(float value) {#setKerningMinimalSize-float-}
```
public final void setKerningMinimalSize(float value)
```

커닝을 활성화해야 하는 최소 글꼴 크기를 반환하거나 설정합니다. **Float.NaN**는 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기  float .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |
### getLanguageId() {#getLanguageId--}
```
public final String getLanguageId()
```

교정 언어의 Id를 반환하거나 설정합니다. 맞춤법 및 문법 검사에 사용됩니다. 읽기/쓰기 String.

**반환:**
java.lang.String
### setLanguageId(String value) {#setLanguageId-java.lang.String-}
```
public final void setLanguageId(String value)
```

교정 언어의 Id를 반환하거나 설정합니다. 맞춤법 및 문법 검사에 사용됩니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public final String getAlternativeLanguageId()
```

대체 언어의 Id를 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**
java.lang.String
### setAlternativeLanguageId(String value) {#setAlternativeLanguageId-java.lang.String-}
```
public final void setAlternativeLanguageId(String value)
```

대체 언어의 Id를 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getSpacing() {#getSpacing--}
```
public final float getSpacing()
```

문자 간 간격 증가값을 반환하거나 설정합니다. **Float.NaN**는 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기  float .

**반환:**
float
### setSpacing(float value) {#setSpacing-float-}
```
public final void setSpacing(float value)
```

문자 간 간격 증가값을 반환하거나 설정합니다. **Float.NaN**는 값이 정의되지 않았으며 마스터에서 상속되어야 함을 의미합니다. 읽기/쓰기  float .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |
### getSpellCheck() {#getSpellCheck--}
```
public final boolean getSpellCheck()
```

텍스트 일부에 대해 맞춤법 검사가 활성화되어 있는지 여부를 가져오거나 설정합니다. 이 속성이 false로 설정되면 텍스트 요소에 대한 맞춤법 검사가 억제됩니다. true로 설정하면 맞춤법 검사가 허용됩니다. 기본값은 false 입니다.

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

**반환:**
boolean
### setSpellCheck(boolean value) {#setSpellCheck-boolean-}
```
public                  똑똑 =   
```

텍스트 일부에 대해 맞춤법 검사가 활성화되어 있는지 여부를 가져오거나 설정합니다. 이 속성이 false로 설정되면 텍스트 요소에 대한 맞춤법 검사가 억제됩니다. true로 설정하면 맞춤법 검사가 허용됩니다. 기본값은 false 입니다.

--------------------

> ```
> Next example demonstrates enabling the SpellCheck flag before saving the presentation:
>  
>  Presentation pres = new Presentation("input.pptx");
>  try {
>      // 첫 번째 슬라이드의 첫 번째 도형 안에 있는 텍스트 첫 번째 부분에 접근
>      IPortion portion = ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).
>              getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // 이 텍스트 부분에 대한 맞춤법 검사를 활성화
>      portion.getPortionFormat().setSpellCheck(true);
>      // 수정된 프레젠테이션을 저장
>      pres.save("output-with-spellcheck.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |