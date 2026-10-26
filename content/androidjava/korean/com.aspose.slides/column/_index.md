---
title: Column
second_title: Aspose.Slides for Android - Java API 참조
description: 테이블의 열을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/column/
---
**상속:**  
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**전체 구현된 인터페이스:**  
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)  
```
public final class Column extends CellCollection implements IColumn
```

테이블의 열을 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | 열의 너비를 반환하거나 설정합니다. |
| [setWidth(double value)](#setWidth-double-) | 열의 너비를 반환하거나 설정합니다. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | 정의된 부분 형식 속성을 모든 열 셀의 부분에 설정합니다. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | 정의된 단락 형식 속성을 모든 열 셀의 단락에 설정합니다. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | 정의된 텍스트 프레임 형식 속성을 모든 열 셀의 텍스트 프레임에 설정합니다. |
| [getColumnFormat()](#getColumnFormat--) | 이 열에 대한 형식 속성을 포함하는 ColumnFormat 객체를 반환합니다. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```

열의 너비를 반환하거나 설정합니다. 읽기/쓰기 double.

**반환값:**  
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

열의 너비를 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

정의된 부분 형식 속성을 모든 열 셀의 부분에 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | 필요한 속성이 설정된 IPortionFormat 객체. |
### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

정의된 단락 형식 속성을 모든 열 셀의 단락에 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | 필요한 속성이 설정된 IParagraphFormat 객체. |
### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

정의된 텍스트 프레임 형식 속성을 모든 열 셀의 텍스트 프레임에 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | 필요한 속성이 설정된 ITextFrameFormat 객체. |
### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```

이 열에 대한 형식 속성을 포함하는 ColumnFormat 객체를 반환합니다. 읽기 전용 [IColumnFormat](../../com.aspose.slides/icolumnformat).

**반환값:**  
[IColumnFormat](../../com.aspose.slides/icolumnformat)