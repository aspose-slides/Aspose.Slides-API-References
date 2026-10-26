---
title: ICellFormat
second_title: Aspose.Slides for Android용 Java API 레퍼런스
description: 테이블 셀의 형식을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

테이블 셀의 형식을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | 셀 채우기 속성 객체를 반환합니다. |
| [getBorderLeft()](#getBorderLeft--) | 왼쪽 테두리 선 속성 객체를 반환합니다. |
| [getBorderTop()](#getBorderTop--) | 위쪽 테두리 선 속성 객체를 반환합니다. |
| [getBorderRight()](#getBorderRight--) | 오른쪽 테두리 선 속성 객체를 반환합니다. |
| [getBorderBottom()](#getBorderBottom--) | 아래쪽 테두리 선 속성 객체를 반환합니다. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | 왼쪽 위에서 오른쪽 아래까지 대각선 선 속성 객체를 반환합니다. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | 왼쪽 아래에서 오른쪽 위까지 대각선 선 속성 객체를 반환합니다. |
| [getTransparency()](#getTransparency--) | 채우기 색상의 투명도를 가져오거나 설정합니다. |
| [setTransparency(float value)](#setTransparency-float-) | 채우기 색상의 투명도를 가져오거나 설정합니다. |
| [getEffective()](#getEffective--) | 상속 및 테이블 스타일이 적용된 실제 셀 서식 속성을 가져옵니다. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


셀 채우기 속성 객체를 반환합니다. 읽기 전용 [IFillFormat](../../com.aspose.slides/ifillformat).

**반환값:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```


왼쪽 테두리 선 속성 객체를 반환합니다. 읽기 전용 [ILineFormat](../../com.aspose.slides/ilineformat).

**반환값:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```


위쪽 테두리 선 속성 객체를 반환합니다. 읽기 전용 [ILineFormat](../../com.aspose.slides/ilineformat).

**반환값:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```


오른쪽 테두리 선 속성 객체를 반환합니다. 읽기 전용 [ILineFormat](../../com.aspose.slides/ilineformat).

**반환값:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```


아래쪽 테두리 선 속성 객체를 반환합니다. 읽기 전용 [ILineFormat](../../com.aspose.slides/ilineformat).

**반환값:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```


왼쪽 위에서 오른쪽 아래까지 대각선 선 속성 객체를 반환합니다. 읽기 전용 [ILineFormat](../../com.aspose.slides/ilineformat).

**반환값:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```


왼쪽 아래에서 오른쪽 위까지 대각선 선 속성 객체를 반환합니다. 읽기 전용 [ILineFormat](../../com.aspose.slides/ilineformat).

**반환값:**
[ILineFormat](../../com.aspose.slides/ilineformat)
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
public abstract ICellFormatEffectiveData getEffective()
```


상속 및 테이블 스타일이 적용된 실제 셀 서식 속성을 가져옵니다.

**반환값:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - 하나의 [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).