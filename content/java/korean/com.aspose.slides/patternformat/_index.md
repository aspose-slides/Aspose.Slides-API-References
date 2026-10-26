---
title: PatternFormat
second_title: Aspose.Slides for Java API 레퍼런스
description: 모양을 채우기 위한 패턴을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/patternformat/
---
**상속:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)  
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

모양을 채우기 위한 패턴을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | 패턴 스타일을 반환하거나 설정합니다. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | 패턴 스타일을 반환하거나 설정합니다. |
| [getForeColor()](#getForeColor--) | 전경 패턴 색상을 반환합니다. |
| [getBackColor()](#getBackColor--) | 배경 패턴 색상을 반환합니다. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | 지정된 색상으로 패턴 채우기를 위한 타일 이미지를 생성합니다. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | 패턴 채우기를 위한 타일 이미지를 생성합니다. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환값:**  
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

패턴 스타일을 반환하거나 설정합니다. 읽기/쓰기 [PatternStyle](../../com.aspose.slides/patternstyle).

**반환값:**  
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

패턴 스타일을 반환하거나 설정합니다. 읽기/쓰기 [PatternStyle](../../com.aspose.slides/patternstyle).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

전경 패턴 색상을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환값:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

배경 패턴 색상을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환값:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```

지정된 색상으로 패턴 채우기를 위한 타일 이미지를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| background | java.awt.Color | 패턴에 대한 배경 java.awt.Color |
| foreground | java.awt.Color | 패턴에 대한 전경 java.awt.Color |

**반환값:**  
[IImage](../../com.aspose.slides/iimage) - 타일 [IImage](../../com.aspose.slides/iimage).
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```

패턴 채우기를 위한 타일 이미지를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| styleColor | java.awt.Color | 기본 java.awt.Color |

**반환값:**  
[IImage](../../com.aspose.slides/iimage) - 타일 [IImage](../../com.aspose.slides/iimage).