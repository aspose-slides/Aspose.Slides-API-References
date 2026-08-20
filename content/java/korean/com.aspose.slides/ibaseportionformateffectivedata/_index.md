---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Base interface for immutable objects which contain effective text portion formatting properties.
type: docs
url: /ko/com.aspose.slides/ibaseportionformateffectivedata/
---```
public interface IBasePortionFormatEffectiveData
```

유효한 텍스트 구문 형식 속성을 포함하는 불변 객체를 위한 기본 인터페이스입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | 텍스트 외곽선을 위한 LineFormat 속성을 반환합니다. |
| [getFillFormat()](#getFillFormat--) | 텍스트 FillFormat 속성을 반환합니다. |
| [getEffectFormat()](#getEffectFormat--) | 텍스트 EffectFormat 속성을 반환합니다. |
| [getHighlightColor()](#getHighlightColor--) | 텍스트 강조에 사용되는 색을 반환합니다. |
| [getUnderlineLineFormat()](#getUnderlineLineFormat--) | 밑줄 라인의 외곽선을 위한 LineFormat 속성을 반환합니다. |
| [getUnderlineFillFormat()](#getUnderlineFillFormat--) | 밑줄 라인의 FillFormat 속성을 반환합니다. |
| [getFontBold()](#getFontBold--) | 글꼴이 굵게 표시되는지 여부를 판단합니다. |
| [getFontItalic()](#getFontItalic--) | 글꼴이 이탤릭인지 여부를 판단합니다. |
| [getKumimoji()](#getKumimoji--) | 숫자가 텍스트 동아시아 언어 전용 수직 레이아웃을 무시해야 하는지 여부를 판단합니다. |
| [getNormaliseHeight()](#getNormaliseHeight--) | 텍스트 높이를 정규화해야 하는지 여부를 판단합니다. |
| [getProofDisabled()](#getProofDisabled--) | 텍스트에 교정 적용을 하지 않아야 하는지 여부를 판단합니다. |
| [getFontUnderline()](#getFontUnderline--) | 텍스트 밑줄 유형을 반환합니다. |
| [getTextCapType()](#getTextCapType--) | 텍스트 대소문자 변환 유형을 반환합니다. |
| [getStrikethroughType()](#getStrikethroughType--) | 텍스트 취소선 유형을 반환합니다. |
| [getSmartTagClean()](#getSmartTagClean--) | 스마트 태그를 정리해야 하는지 여부를 판단합니다. |
| [isHardUnderlineLine()](#isHardUnderlineLine--) | 밑줄 스타일이 자체 LineFormat 속성을 가지고 있는지, 텍스트의 LineFormat 속성에서 상속받는지 여부를 판단합니다. |
| [isHardUnderlineFill()](#isHardUnderlineFill--) | 밑줄 스타일이 자체 FillFormat 속성을 가지고 있는지, 텍스트의 FillFormat 속성에서 상속받는지 여부를 판단합니다. |
| [getFontHeight()](#getFontHeight--) | 텍스트 구문의 글꼴 높이를 포인트 단위로 반환합니다. |
| [getLatinFont()](#getLatinFont--) | 라틴 글꼴 정보를 반환합니다. |
| [getEastAsianFont()](#getEastAsianFont--) | 동아시아 글꼴 정보를 반환합니다. |
| [getComplexScriptFont()](#getComplexScriptFont--) | 복합 스크립트 글꼴 정보를 반환합니다. |
| [getSymbolFont()](#getSymbolFont--) | 기호 글꼴 정보를 반환합니다. |
| [getEscapement()](#getEscapement--) | 위첨자 또는 아래첨자 텍스트를 반환합니다. |
| [getKerningMinimalSize()](#getKerningMinimalSize--) | 커닝이 적용되는 최소 글꼴 크기를 반환합니다. |
| [getLanguageId()](#getLanguageId--) | 언어의 Id를 반환합니다. |
| [getAlternativeLanguageId()](#getAlternativeLanguageId--) | 대체 언어의 Id를 반환합니다. |
| [getSpacing()](#getSpacing--) | 문자 간 간격 증가값을 포인트 단위로 반환합니다. |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormatEffectiveData getLineFormat()
```

텍스트 외곽선을 위한 LineFormat 속성을 반환합니다. 읽기 전용 [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**반환:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

텍스트 FillFormat 속성을 반환합니다. 읽기 전용 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**반환:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```

텍스트 EffectFormat 속성을 반환합니다. 읽기 전용 [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**반환:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)
### getHighlightColor() {#getHighlightColor--}
```
public abstract Color getHighlightColor()
```

텍스트 강조에 사용되는 색을 반환합니다. 읽기 전용 java.awt.Color.

**반환:**
java.awt.Color
### getUnderlineLineFormat() {#getUnderlineLineFormat--}
```
public abstract ILineFormatEffectiveData getUnderlineLineFormat()
```

밑줄 라인의 외곽선을 위한 LineFormat 속성을 반환합니다. 읽기 전용 [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).

**반환:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)
### getUnderlineFillFormat() {#getUnderlineFillFormat--}
```
public abstract IFillFormatEffectiveData getUnderlineFillFormat()
```

밑줄 라인의 FillFormat 속성을 반환합니다. 읽기 전용 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**반환:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getFontBold() {#getFontBold--}
```
public abstract boolean getFontBold()
```

글꼴이 굵게 표시되는지 여부를 판단합니다. 읽기 전용 boolean.

**반환:**
boolean
### getFontItalic() {#getFontItalic--}
```
public abstract boolean getFontItalic()
```

글꼴이 이탤릭인지 여부를 판단합니다. 읽기 전용 boolean.

**반환:**
boolean
### getKumimoji() {#getKumimoji--}
```
public abstract boolean getKumimoji()
```

숫자가 텍스트 동아시아 언어 전용 수직 레이아웃을 무시해야 하는지 여부를 판단합니다. 읽기 전용 boolean.

**반환:**
boolean
### getNormaliseHeight() {#getNormaliseHeight--}
```
public abstract boolean getNormaliseHeight()
```

텍스트 높이를 정규화해야 하는지 여부를 판단합니다. 읽기 전용 boolean.

**반환:**
boolean
### getProofDisabled() {#getProofDisabled--}
```
public abstract boolean getProofDisabled()
```

텍스트에 교정 적용을 하지 않아야 하는지 여부를 판단합니다. 읽기 전용 boolean.

**반환:**
boolean
### getFontUnderline() {#getFontUnderline--}
```
public abstract byte getFontUnderline()
```

텍스트 밑줄 유형을 반환합니다. 읽기 전용 [TextUnderlineType](../../com.aspose.slides/textunderlinetype).

**반환:**
byte
### getTextCapType() {#getTextCapType--}
```
public abstract byte getTextCapType()
```

텍스트 대소문자 변환 유형을 반환합니다. 읽기 전용 [TextCapType](../../com.aspose.slides/textcaptype).

**반환:**
byte
### getStrikethroughType() {#getStrikethroughType--}
```
public abstract byte getStrikethroughType()
```

텍스트 취소선 유형을 반환합니다. 읽기 전용 [TextStrikethroughType](../../com.aspose.slides/textstrikethroughtype).

**반환:**
byte
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

스마트 태그를 정리해야 하는지 여부를 판단합니다. 읽기 전용 boolean.

**반환:**
boolean
### isHardUnderlineLine() {#isHardUnderlineLine--}
```
public abstract boolean isHardUnderlineLine()
```

밑줄 스타일이 자체 LineFormat 속성을 가지고 있는지, 텍스트의 LineFormat 속성에서 상속받는지 여부를 판단합니다. 읽기 전용 boolean.

**반환:**
boolean
### isHardUnderlineFill() {#isHardUnderlineFill--}
```
public abstract boolean isHardUnderlineFill()
```

밑줄 스타일이 자체 FillFormat 속성을 가지고 있는지, 텍스트의 FillFormat 속성에서 상속받는지 여부를 판단합니다. 읽기 전용 boolean.

**반환:**
boolean
### getFontHeight() {#getFontHeight--}
```
public abstract float getFontHeight()
```

텍스트 구문의 글꼴 높이를 포인트 단위로 반환합니다. 읽기 전용 float.

**반환:**
float
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

라틴 글꼴 정보를 반환합니다. 읽기 전용 [IFontData](../../com.aspose.slides/ifontdata).

**반환:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

동아시아 글꼴 정보를 반환합니다. 읽기 전용 [IFontData](../../com.aspose.slides/ifontdata).

**반환:**
[IFontData](../../com.aspose.slides/ifontdata)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

복합 스크립트 글꼴 정보를 반환합니다. 읽기 전용 [IFontData](../../com.aspose.slides/ifontdata).

**반환:**
[IFontData](../../com.aspose.slides/ifontdata)
### getSymbolFont() {#getSymbolFont--}
```
public abstract IFontData getSymbolFont()
```

기호 글꼴 정보를 반환합니다. 읽기 전용 [IFontData](../../com.aspose.slides/ifontdata).

**반환:**
[IFontData](../../com.aspose.slides/ifontdata)
### getEscapement() {#getEscapement--}
```
public abstract float getEscapement()
```

위첨자 또는 아래첨자 텍스트를 반환합니다. -100% (아래첨자)에서 100% (위첨자)까지의 값. 읽기 전용 float.

**반환:**
float
### getKerningMinimalSize() {#getKerningMinimalSize--}
```
public abstract float getKerningMinimalSize()
```

커닝이 적용되는 최소 글꼴 크기를 반환합니다. 읽기 전용 float.

**반환:**
float
### getLanguageId() {#getLanguageId--}
```
public abstract String getLanguageId()
```

언어의 Id를 반환합니다. 읽기 전용 String.

**반환:**
java.lang.String
### getAlternativeLanguageId() {#getAlternativeLanguageId--}
```
public abstract String getAlternativeLanguageId()
```

대체 언어의 Id를 반환합니다. 읽기 전용 String.

**반환:**
java.lang.String
### getSpacing() {#getSpacing--}
```
public abstract float getSpacing()
```

문자 간 간격 증가값을 포인트 단위로 반환합니다. 읽기 전용 float.

**반환:**
float