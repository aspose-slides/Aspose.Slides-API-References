---
title: IShapeStyle
second_title: Aspose.Slides for Android Java API 참조
description: 도형 스타일 참조를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

도형 스타일 참조를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLineColor()](#getLineColor--) | 도형의 외곽선 색상을 반환합니다. |
| [getLineStyleIndex()](#getLineStyleIndex--) | 스타일 행렬에서 선의 열 인덱스를 반환하거나 설정합니다. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | 스타일 행렬에서 선의 열 인덱스를 반환하거나 설정합니다. |
| [getFillColor()](#getFillColor--) | 도형의 채우기 색상을 반환합니다. |
| [getFillStyleIndex()](#getFillStyleIndex--) | 스타일 행렬에서 도형의 채우기 열 인덱스를 반환하거나 설정합니다. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | 스타일 행렬에서 도형의 채우기 열 인덱스를 반환하거나 설정합니다. |
| [getEffectColor()](#getEffectColor--) | 도형의 효과 색상을 반환합니다. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | 스타일 행렬에서 도형의 효과 열 인덱스를 반환하거나 설정합니다. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | 스타일 행렬에서 도형의 효과 열 인덱스를 반환하거나 설정합니다. |
| [getFontColor()](#getFontColor--) | 도형의 글꼴 색상을 반환합니다. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | 글꼴 컬렉션에서 도형의 글꼴 인덱스를 반환하거나 설정합니다. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | 글꼴 컬렉션에서 도형의 글꼴 인덱스를 반환하거나 설정합니다. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

도형의 외곽선 색상을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

스타일 행렬에서 선의 열 인덱스를 반환하거나 설정합니다. 읽기/쓰기 int.

**반환:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

스타일 행렬에서 선의 열 인덱스를 반환하거나 설정합니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

도형의 채우기 색상을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

스타일 행렬에서 도형의 채우기 열 인덱스를 반환하거나 설정합니다. 0은 채우기 없음, 양수 값은 테마의 채우기 스타일 인덱스, 음수 값은 테마의 배경 스타일 인덱스입니다. 읽기/쓰기 short.

**반환:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

스타일 행렬에서 도형의 채우기 열 인덱스를 반환하거나 설정합니다. 0은 채우기 없음, 양수 값은 테마의 채우기 스타일 인덱스, 음수 값은 테마의 배경 스타일 인덱스입니다. 읽기/쓰기 short.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

도형의 효과 색상을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

스타일 행렬에서 도형의 효과 열 인덱스를 반환하거나 설정합니다. 읽기/쓰기 long.

**반환:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

스타일 행렬에서 도형의 효과 열 인덱스를 반환하거나 설정합니다. 읽기/쓰기 long.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

도형의 글꼴 색상을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

글꼴 컬렉션에서 도형의 글꼴 인덱스를 반환하거나 설정합니다. 읽기/쓰기 [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**반환:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

글꼴 컬렉션에서 도형의 글꼴 인덱스를 반환하거나 설정합니다. 읽기/쓰기 [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |