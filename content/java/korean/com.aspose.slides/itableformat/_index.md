---
title: ITableFormat
second_title: Aspose.Slides for Java API Reference
description: 테이블의 형식을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

테이블의 형식을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returns a table fill properties object. |
| [getTransparency()](#getTransparency--) | Gets or sets the transparency of the fill color. |
| [setTransparency(float value)](#setTransparency-float-) | Gets or sets the transparency of the fill color. |
| [getEffective()](#getEffective--) | Gets effective table formatting properties with inheritance and table styles applied. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


테이블 채우기 속성 객체를 반환합니다. 읽기 전용 [IFillFormat](../../com.aspose.slides/ifillformat).

**반환값:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


채우기 색상의 투명도를 가져오거나 설정합니다. 읽기/쓰기  float .

**반환값:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


채우기 색상의 투명도를 가져오거나 설정합니다. 읽기/쓰기  float .

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


상속 및 테이블 스타일이 적용된 효과적인 테이블 서식 속성을 가져옵니다.

**반환값:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).