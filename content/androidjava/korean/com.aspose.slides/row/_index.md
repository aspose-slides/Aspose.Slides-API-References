---
title: Row
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: 테이블의 행을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/row/
---
**상속:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**구현된 모든 인터페이스:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

테이블의 행을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getHeight()](#getHeight--) | 행의 높이를 반환합니다. |
| [getMinimalHeight()](#getMinimalHeight--) | 행의 최소 가능한 높이를 반환하거나 설정합니다. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | 행의 최소 가능한 높이를 반환하거나 설정합니다. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | 정의된 portion 형식 속성을 모든 행 셀의 portion에 설정합니다. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | 정의된 paragraph 형식 속성을 모든 행 셀의 paragraph에 설정합니다. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | 정의된 text frame 형식 속성을 모든 행 셀의 text frame에 설정합니다. |
| [getRowFormat()](#getRowFormat--) | 이 행에 대한 서식 속성을 포함하는 RowFormat 객체를 반환합니다. |
### getHeight() {#getHeight--}
```
public final double getHeight()
```


행의 높이를 반환합니다. 읽기 전용 double.

**반환:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```


행의 최소 가능한 높이를 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```


행의 최소 가능한 높이를 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


정의된 portion 형식 속성을 모든 행 셀의 portion에 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | 필요한 속성이 설정된 IPortionFormat 객체. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


정의된 paragraph 형식 속성을 모든 행 셀의 paragraph에 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | 필요한 속성이 설정된 IParagraphFormat 객체. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


정의된 text frame 형식 속성을 모든 행 셀의 text frame에 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | 필요한 속성이 설정된 ITextFrameFormat 객체. |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```


이 행에 대한 서식 속성을 포함하는 RowFormat 객체를 반환합니다. 읽기 전용 [IRowFormat](../../com.aspose.slides/irowformat).

**반환:**
[IRowFormat](../../com.aspose.slides/irowformat)