---
title: ChartTextFormat
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 차트 텍스트 요소에 대한 기본 텍스트 서식을 지정합니다.
type: docs
url: /ko/com.aspose.slides/charttextformat/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IChartTextFormat](../../com.aspose.slides/icharttextformat), com.aspose.slides.IDOMObject  
```
public class ChartTextFormat implements IChartTextFormat, IDOMObject
```

차트 텍스트 요소에 대한 기본 텍스트 형식을 지정합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | 지정된 텍스트 프레임에 텍스트 형식을 복사합니다. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | 지정된 텍스트 프레임에서 텍스트 형식을 복사합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```

TextBlockFormat. 읽기 전용 [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**반환값:**  
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)

### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```

ParagraphFormat. 읽기 전용 [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**반환값:**  
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)

### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```

PortionFormat. 읽기 전용 [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**반환값:**  
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)

### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```

지정된 텍스트 프레임에 텍스트 형식을 복사합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | 텍스트 형식을 복사할 텍스트 프레임입니다. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```

지정된 텍스트 프레임에서 텍스트 형식을 복사합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | 텍스트 형식을 복사할 텍스트 프레임입니다. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 개체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**  
com.aspose.slides.IDOMObject