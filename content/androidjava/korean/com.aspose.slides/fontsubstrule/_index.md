---
title: FontSubstRule
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 폰트 대체 정보를 나타냅니다
type: docs
url: /ko/com.aspose.slides/fontsubstrule/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

폰트 대체 정보를 나타냅니다
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | 새 인스턴스를 생성합니다. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | 새 인스턴스를 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | 대체할 폰트. |
| [getDestFont()](#getDestFont--) | 대체에 사용할 폰트. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | 대체에 적용할 규칙. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


새 인스턴스를 생성합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | 원본 폰트. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 대상 폰트. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


새 인스턴스를 생성합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | 원본 폰트. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 대상 폰트. |
| fontSubstRule | int | 폰트 대체 규칙. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


대체할 폰트. 읽기 전용 [IFontData](../../com.aspose.slides/ifontdata).

**반환값:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


대체에 사용할 폰트. 읽기 전용 [IFontData](../../com.aspose.slides/ifontdata).

**반환값:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


대체에 적용할 규칙. 읽기 전용 [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**반환값:**
int