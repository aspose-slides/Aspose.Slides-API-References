---
title: ShapeStyle
second_title: Aspose.Slides for Android용 Java API 레퍼런스
description: 형상의 스타일 참조를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/shapestyle/
---
**상속:**  
java.lang.Object, com.aspose.slides.DomObject

**모든 구현 인터페이스:**  
[com.aspose.slides.IShapeStyle](../../com.aspose.slides/ishapestyle)  
```
public class ShapeStyle extends DomObject<Shape> implements IShapeStyle
```

형상의 스타일 참조를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLineColor()](#getLineColor--) | 형상의 외곽선 색상을 반환합니다. |
| [getLineStyleIndex()](#getLineStyleIndex--) | 스타일 매트릭스에서 선의 열 인덱스를 반환하거나 설정합니다. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | 스타일 매트릭스에서 선의 열 인덱스를 반환하거나 설정합니다. |
| [getFillColor()](#getFillColor--) | 형상의 채우기 색상을 반환합니다. |
| [getFillStyleIndex()](#getFillStyleIndex--) | 스타일 매트릭스에서 형상의 채우기 열 인덱스를 반환하거나 설정합니다. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | 스타일 매트릭스에서 형상의 채우기 열 인덱스를 반환하거나 설정합니다. |
| [getEffectColor()](#getEffectColor--) | 형상의 효과 색상을 반환합니다. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | 스타일 매트릭스에서 형상의 효과 열 인덱스를 반환하거나 설정합니다. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | 스타일 매트릭스에서 형상의 효과 열 인덱스를 반환하거나 설정합니다. |
| [getFontColor()](#getFontColor--) | 형상의 글꼴 색상을 반환합니다. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | 글꼴 컬렉션에서 형상의 글꼴 인덱스를 반환하거나 설정합니다. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | 글꼴 컬렉션에서 형상의 글꼴 인덱스를 반환하거나 설정합니다. |

### getLineColor() {#getLineColor--}
```
public final IColorFormat getLineColor()
```

형상의 외곽선 색상을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getLineStyleIndex() {#getLineStyleIndex--}
```
public final int getLineStyleIndex()
```

스타일 매트릭스에서 선의 열 인덱스를 반환하거나 설정합니다. 읽기/쓰기 int.

**반환:**  
int

### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public final void setLineStyleIndex(int value)
```

스타일 매트릭스에서 선의 열 인덱스를 반환하거나 설정합니다. 읽기/쓰기 int.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getFillColor() {#getFillColor--}
```
public final IColorFormat getFillColor()
```

형상의 채우기 색상을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getFillStyleIndex() {#getFillStyleIndex--}
```
public final short getFillStyleIndex()
```

스타일 매트릭스에서 형상의 채우기 열 인덱스를 반환하거나 설정합니다. 0은 채우기 없음, 양수 값은 테마의 채우기 스타일 인덱스, 음수 값은 테마의 배경 스타일 인덱스를 의미합니다. 읽기/쓰기 short.

**반환:**  
short

### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public final void setFillStyleIndex(short value)
```

스타일 매트릭스에서 형상의 채우기 열 인덱스를 반환하거나 설정합니다. 0은 채우기 없음, 양수 값은 테마의 채우기 스타일 인덱스, 음수 값은 테마의 배경 스타일 인덱스를 의미합니다. 읽기/쓰기 short.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | short |  |

### getEffectColor() {#getEffectColor--}
```
public final IColorFormat getEffectColor()
```

형상의 효과 색상을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public final long getEffectStyleIndex()
```

스타일 매트릭스에서 형상의 효과 열 인덱스를 반환하거나 설정합니다. 읽기/쓰기 long.

**반환:**  
long

### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public final void setEffectStyleIndex(long value)
```

스타일 매트릭스에서 형상의 효과 열 인덱스를 반환하거나 설정합니다. 읽기/쓰기 long.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | long |  |

### getFontColor() {#getFontColor--}
```
public final IColorFormat getFontColor()
```

형상의 글꼴 색상을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public final byte getFontCollectionIndex()
```

글꼴 컬렉션에서 형상의 글꼴 인덱스를 반환하거나 설정합니다. 읽기/쓰기 [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**반환:**  
byte

### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public final void setFontCollectionIndex(byte value)
```

글꼴 컬렉션에서 형상의 글꼴 인덱스를 반환하거나 설정합니다. 읽기/쓰기 [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |