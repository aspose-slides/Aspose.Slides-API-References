---
title: CellFormat
second_title: Aspose.Slides for Android용 Java API 레퍼런스
description: 테이블 셀의 형식을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/cellformat/
---
**상속:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**구현된 모든 인터페이스:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

테이블 셀의 형식을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | 셀 채우기 속성 객체를 반환합니다. |
| [getBorderLeft()](#getBorderLeft--) | 왼쪽 테두리 선 속성 객체를 반환합니다. |
| [getBorderTop()](#getBorderTop--) | 위쪽 테두리 선 속성 객체를 반환합니다. |
| [getBorderRight()](#getBorderRight--) | 오른쪽 테두리 선 속성 객체를 반환합니다. |
| [getBorderBottom()](#getBorderBottom--) | 아래쪽 테두리 선 속성 객체를 반환합니다. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | 왼쪽 위에서 오른쪽 아래로 대각선 선 속성 객체를 반환합니다. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | 왼쪽 아래에서 오른쪽 위로 대각선 선 속성 객체를 반환합니다. |
| [getEffective()](#getEffective--) | 상속 및 테이블 스타일이 적용된 효과적인 셀 서식 속성을 가져옵니다. |
| [getTransparency()](#getTransparency--) | 채우기 색상의 투명도를 가져오거나 설정합니다. |
| [setTransparency(float value)](#setTransparency-float-) | 채우기 색상의 투명도를 가져오거나 설정합니다. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


버전. 읽기 전용 long.

**반환:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


셀 채우기 속성 객체를 반환합니다. 읽기 전용 [IFillFormat](../../com.aspose.slides/ifillformat).

**반환:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```


왼쪽 테두리 선 속성 객체를 반환합니다. 읽기 전용 [ILineFormat](../../com.aspose.slides/ilineformat).

**반환:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```


위쪽 테두리 선 속성 객체를 반환합니다. 읽기 전용 [ILineFormat](../../com.aspose.slides/ilineformat).

**반환:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```


오른쪽 테두리 선 속성 객체를 반환합니다. 읽기 전용 [ILineFormat](../../com.aspose.slides/ilineformat).

**반환:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```


아래쪽 테두리 선 속성 객체를 반환합니다. 읽기 전용 [ILineFormat](../../com.aspose.slides/ilineformat).

**반환:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```


왼쪽 위에서 오른쪽 아래로 대각선 선 속성 객체를 반환합니다. 읽기 전용 [ILineFormat](../../com.aspose.slides/ilineformat).

**반환:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```


왼쪽 아래에서 오른쪽 위로 대각선 선 속성 객체를 반환합니다. 읽기 전용 [ILineFormat](../../com.aspose.slides/ilineformat).

**반환:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```


상속 및 테이블 스타일이 적용된 효과적인 셀 서식 속성을 가져옵니다.

--------------------

> ```
> 이 예제는 다양한 표 논리 부분에 대한 효과적인 채우기 형식을 가져오는 방법을 보여줍니다.
>  셀 서식은 항상 행 서식보다 우선 순위가 높으며, 행은 열보다, 열은 전체 표보다 우선 순위가 높다는 점에 유의하십시오.
>  따라서 최종적으로 CellFormatEffectiveData 속성이 표를 그리는 데 항상 사용됩니다. 다음 코드는 API 사용 예시일 뿐입니다.
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).RowFormat.GetEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - 하나의 [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```


채우기 색상의 투명도를 가져오거나 설정합니다. 읽기/쓰기  float .

**반환:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```


채우기 색상의 투명도를 가져오거나 설정합니다. 읽기/쓰기  float .

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |