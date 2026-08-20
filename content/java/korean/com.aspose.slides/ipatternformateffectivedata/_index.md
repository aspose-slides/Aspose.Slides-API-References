---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: 효과적인 패턴 채우기 속성을 포함하는 불변 객체.
type: docs
url: /ko/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

효과적인 패턴 채우기 속성을 포함하는 불변 객체.

--------------------

이 인터페이스는 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) 및 [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)의 일부로 사용됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | 패턴 스타일을 반환합니다. |
| [getForeColor()](#getForeColor--) | 전경 패턴 색상을 반환합니다. |
| [getBackColor()](#getBackColor--) | 배경 패턴 색상을 반환합니다. |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | 지정된 색상으로 패턴 채우기를 위한 타일 이미지를 생성합니다. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


패턴 스타일을 반환합니다. 읽기 전용 [PatternStyle](../../com.aspose.slides/patternstyle).

**반환:**  
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```


전경 패턴 색상을 반환합니다. 읽기 전용 java.awt.Color.

**반환:**  
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```


배경 패턴 색상을 반환합니다. 읽기 전용 java.awt.Color.

**반환:**  
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```


지정된 색상으로 패턴 채우기를 위한 타일 이미지를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| background | java.awt.Color | 패턴에 대한 배경 java.awt.Color. |
| foreground | java.awt.Color | 패턴에 대한 전경 java.awt.Color. |

**반환:**  
[IImage](../../com.aspose.slides/iimage) - 타일 [IImage](../../com.aspose.slides/iimage).