---
title: FontScheme
second_title: Aspose.Slides for Java API 레퍼런스
description: 테마에서 정의된 글꼴을 저장합니다.
type: docs
url: /ko/com.aspose.slides/fontscheme/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontScheme](../../com.aspose.slides/ifontscheme), com.aspose.slides.IDOMObject
```
public class FontScheme implements IFontScheme, IDOMObject
```

테마에서 정의된 글꼴을 저장합니다.
## Methods

| Method | Description |
| --- | --- |
| [getMinor()](#getMinor--) | 슬라이드의 "body" 부분에 대한 글꼴 컬렉션을 반환합니다. |
| [getMajor()](#getMajor--) | 슬라이드의 "heading" 부분에 대한 글꼴 컬렉션을 반환합니다. |
| [getName()](#getName--) | 글꼴 스킴 이름을 반환합니다. |
| [setName(String value)](#setName-java.lang.String-) | 글꼴 스킴 이름을 반환합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getMinor() {#getMinor--}
```
public final IFonts getMinor()
```

슬라이드의 "body" 부분에 대한 글꼴 컬렉션을 반환합니다. 읽기 전용 [IFonts](../../com.aspose.slides/ifonts).

**Returns:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public final IFonts getMajor()
```

슬라이드의 "heading" 부분에 대한 글꼴 컬렉션을 반환합니다. 읽기 전용 [IFonts](../../com.aspose.slides/ifonts).

**Returns:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public final String getName()
```

글꼴 스킴 이름을 반환합니다. 읽기/쓰기 String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

글꼴 스킴 이름을 반환합니다. 읽기/쓰기 String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject