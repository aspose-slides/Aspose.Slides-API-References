---
title: IPatternFormat
second_title: Aspose.Slides for Android via Java API Reference
description: 모양을 채우기 위한 패턴을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

모양을 채우는 패턴을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | 패턴 스타일을 반환하거나 설정합니다. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | 패턴 스타일을 반환하거나 설정합니다. |
| [getForeColor()](#getForeColor--) | 전경 패턴 색상을 반환합니다. |
| [getBackColor()](#getBackColor--) | 배경 패턴 색상을 반환합니다. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | 지정된 색상으로 패턴 채우기를 위한 타일 이미지를 생성합니다. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | 패턴 채우기를 위한 타일 이미지를 생성합니다. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

패턴 스타일을 반환하거나 설정합니다. 읽기/쓰기 [PatternStyle](../../com.aspose.slides/patternstyle).

**반환:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

패턴 스타일을 반환하거나 설정합니다. 읽기/쓰기 [PatternStyle](../../com.aspose.slides/patternstyle).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

전경 패턴 색상을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

배경 패턴 색상을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```

지정된 색상으로 패턴 채우기를 위한 타일 이미지를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| background | java.lang.Integer | 패턴을 위한 배경 java.lang.Integer. |
| foreground | java.lang.Integer | 패턴을 위한 전경 java.lang.Integer. |

**반환:**
[IImage](../../com.aspose.slides/iimage) - 타일 android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```

패턴 채우기를 위한 타일 이미지를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| styleColor | java.lang.Integer | ShapeEx의 StyleEx 객체에 정의된 기본 java.lang.Integer. 색상은 이에 따라 달라질 수 있습니다. |

**반환:**
[IImage](../../com.aspose.slides/iimage) - 타일 android.graphics.Bitmap.