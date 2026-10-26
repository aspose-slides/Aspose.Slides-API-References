---
title: ITableFormat
second_title: Aspose.Slides for Android용 Java API 참조
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
| [getFillFormat()](#getFillFormat--) | 테이블 채우기 속성 객체를 반환합니다. |
| [getTransparency()](#getTransparency--) | 채우기 색상의 투명도를 가져오거나 설정합니다. |
| [setTransparency(float value)](#setTransparency-float-) | 채우기 색상의 투명도를 가져오거나 설정합니다. |
| [getEffective()](#getEffective--) | 상속 및 테이블 스타일이 적용된 실제 테이블 서식 속성을 가져옵니다. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

테이블 채우기 속성 객체를 반환합니다. 읽기 전용 [IFillFormat](../../com.aspose.slides/ifillformat).

**반환:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

채우기 색상의 투명도를 가져오거나 설정합니다. 읽기/쓰기  float .

**반환:**
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

상속 및 테이블 스타일이 적용된 실제 테이블 서식 속성을 가져옵니다.

**반환:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).