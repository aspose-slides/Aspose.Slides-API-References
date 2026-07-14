---
title: IChartTextFormat
second_title: Aspose.Slides for Android via Java API Reference
description: 차트는 제한된 텍스트 형식 속성 집합으로 작동합니다.
type: docs
url: /ko/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

차트는 제한된 텍스트 형식 속성 집합으로 작동합니다. IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat 인터페이스가 이 제한된 집합을 설명합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | 차트 텍스트 요소에 대한 형식을 반환합니다. |
| [getParagraphFormat()](#getParagraphFormat--) | 단락 형식을 반환합니다. |
| [getPortionFormat()](#getPortionFormat--) | 부분 형식을 반환합니다. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | 지정된 텍스트 프레임에 텍스트 형식을 복사합니다. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | 지정된 텍스트 프레임에서 텍스트 형식을 복사합니다. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```

차트 텍스트 요소에 대한 형식을 반환합니다. 읽기 전용 [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**반환:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```

단락 형식을 반환합니다. 읽기 전용 [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**반환:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```

부분 형식을 반환합니다. 읽기 전용 [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**반환:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```

지정된 텍스트 프레임에 텍스트 형식을 복사합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | 텍스트 형식을 복사할 텍스트 프레임. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```

지정된 텍스트 프레임에서 텍스트 형식을 복사합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | 텍스트 형식을 복사할 텍스트 프레임. |