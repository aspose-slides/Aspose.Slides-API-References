---
title: RowFormat
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 테이블 행의 형식을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/rowformat/
---
**상속:**
java.lang.Object, com.aspose.slides.DomObject

**모든 구현된 인터페이스:**
[com.aspose.slides.IRowFormat](../../com.aspose.slides/irowformat), com.aspose.slides.IPVIObject
```
public final class RowFormat extends DomObject<Row> implements IRowFormat, IPVIObject
```

테이블 행의 형식을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getEffective()](#getEffective--) | 상속 및 테이블 스타일이 적용된 효과적인 테이블 행 서식 속성을 가져옵니다. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IRowFormatEffectiveData getEffective()
```


상속 및 테이블 스타일이 적용된 효과적인 테이블 행 서식 속성을 가져옵니다.

--------------------

> ```
> 이 예제는 다양한 테이블 논리 부분에 대한 효과적인 채우기 형식을 가져오는 방법을 보여줍니다.
>  셀 서식은 항상 행 서식보다 우선순위가 높고, 행은 열보다, 열은 전체 테이블보다 우선합니다.
>  따라서 최종적으로 CellFormatEffectiveData 속성이 테이블을 그리는 데 사용됩니다. 다음 코드는 API 예시일 뿐입니다.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
[IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata) - 하나의 [IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata).
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


부모 IPresentationComponent을 반환합니다. 읽기 전용 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**반환:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)