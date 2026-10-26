---
title: FontSubstRule
second_title: Aspose.Slides for Java API 레퍼런스
description: 글꼴 치환 정보를 나타냅니다
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

글꼴 치환 정보를 나타냅니다
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | 새 인스턴스를 생성합니다. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | 새 인스턴스를 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | 대체할 글꼴. |
| [getDestFont()](#getDestFont--) | 치환에 사용할 글꼴. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | 치환에 적용할 규칙. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


새 인스턴스를 생성합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | 원본 글꼴. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 대상 글꼴. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


새 인스턴스를 생성합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | 원본 글꼴. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 대상 글꼴. |
| fontSubstRule | int | 글꼴 치환 규칙. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


대체할 글꼴. 읽기 전용 [IFontData](../../com.aspose.slides/ifontdata).

**반환값:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


치환에 사용할 글꼴. 읽기 전용 [IFontData](../../com.aspose.slides/ifontdata).

**반환값:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


치환에 적용할 규칙. 읽기 전용 [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**반환값:**
int