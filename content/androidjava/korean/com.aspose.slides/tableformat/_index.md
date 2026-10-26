---
title: TableFormat
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 테이블의 형식을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/tableformat/
---
**상속:**
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

테이블의 형식을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | 테이블 채우기 속성 개체를 반환합니다. |
| [getTransparency()](#getTransparency--) | 채우기 색상의 투명도를 가져오거나 설정합니다. |
| [setTransparency(float value)](#setTransparency-float-) | 채우기 색상의 투명도를 가져오거나 설정합니다. |
| [getEffective()](#getEffective--) | 상속 및 테이블 스타일이 적용된 효과적인 테이블 서식 속성을 가져옵니다. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

테이블 채우기 속성 개체를 반환합니다. 읽기 전용 [IFillFormat](../../com.aspose.slides/ifillformat).

**반환:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

채우기 색상의 투명도를 가져오거나 설정합니다. 읽기/쓰기 float .

**반환:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

채우기 색상의 투명도를 가져오거나 설정합니다. 읽기/쓰기 float .

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```

상속 및 테이블 스타일이 적용된 효과적인 테이블 서식 속성을 가져옵니다.

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (Table)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - 하나의 [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```

버전. 읽기 전용 long.

**반환:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

부모 IPresentationComponent를 반환합니다. 읽기 전용 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**반환:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)