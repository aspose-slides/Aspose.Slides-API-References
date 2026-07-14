---
title: IDataLabel
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 시리즈 레이블을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/idatalabel/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

시리즈 레이블을 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [isVisible()](#isVisible--) | False는 데이터 레이블이 보이지 않음을 의미합니다(그리고 모든 Show*-플래그(ShowValue, ...)가 false입니다). |
| [hide()](#hide--) | Show*-플래그(ShowValue, ...)를 false 상태로 설정하여 데이터 레이블을 숨깁니다. |
| [getDataLabelFormat()](#getDataLabelFormat--) | 데이터 레이블의 형식을 반환합니다. |
| [getValueFromCell()](#getValueFromCell--) | 워크북 데이터 셀을 가져오거나 설정합니다. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | 워크북 데이터 셀을 가져오거나 설정합니다. |
| [getActualLabelText()](#getActualLabelText--) | DataLabelFormat 설정 또는 TextFrameForOverriding.Text 값을 기반으로 실제 레이블 텍스트를 반환합니다. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False는 데이터 레이블이 보이지 않음을 의미합니다(그리고 모든 Show*-플래그(ShowValue, ...)가 false입니다). 읽기 전용 boolean.

--------------------

데이터 레이블이 보이는 경우 Hide() 메서드로 숨길 수 있습니다. 그러나 데이터 레이블이 보이지 않으면(IsVisible가 false) Show*-플래그(ShowValue, ...)를 true 상태로 설정하여 데이터 레이블을 보이게 할 수 있습니다.

**반환값:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Show*-플래그(ShowValue, ...)를 false 상태로 설정하여 데이터 레이블을 숨깁니다. 이 후 IsVisible는 false가 됩니다.

--------------------

데이터 레이블이 보이지 않으면(IsVisible가 false) Show*-플래그(ShowValue, ...)를 true 상태로 설정하여 데이터 레이블을 보이게 할 수 있습니다.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

데이터 레이블의 형식을 반환합니다. 읽기 전용 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**반환값:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

워크북 데이터 셀을 가져오거나 설정합니다. IDataLabelFormat.ShowLabelValueFromCell 속성이 true인 경우에 적용됩니다.

**반환값:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

워크북 데이터 셀을 가져오거나 설정합니다. IDataLabelFormat.ShowLabelValueFromCell 속성이 true인 경우에 적용됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

DataLabelFormat 설정 또는 TextFrameForOverriding.Text 값을 기반으로 실제 레이블 텍스트를 반환합니다.

**반환값:**
java.lang.String - 실제 레이블 텍스트 문자열