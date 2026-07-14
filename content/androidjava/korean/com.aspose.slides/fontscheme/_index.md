---
title: FontScheme
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 테마에서 정의된 글꼴을 저장합니다.
type: docs
url: /ko/com.aspose.slides/fontscheme/
---
**상속:**  
java.lang.Object

**모든 구현된 인터페이스:**  
[com.aspose.slides.IFontScheme](../../com.aspose.slides/ifontscheme), com.aspose.slides.IDOMObject  
```
public class FontScheme implements IFontScheme, IDOMObject
```

테마에서 정의된 글꼴을 저장합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getMinor()](#getMinor--) | 슬라이드의 "body" 부분에 대한 글꼴 컬렉션을 반환합니다. |
| [getMajor()](#getMajor--) | 슬라이드의 "heading" 부분에 대한 글꼴 컬렉션을 반환합니다. |
| [getName()](#getName--) | 글꼴 스키마 이름을 반환합니다. |
| [setName(String value)](#setName-java.lang.String-) | 글꼴 스키마 이름을 반환합니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getMinor() {#getMinor--}
```
public final IFonts getMinor()
```

슬라이드의 "body" 부분에 대한 글꼴 컬렉션을 반환합니다. 읽기 전용 [IFonts](../../com.aspose.slides/ifonts).

**반환:**  
[IFonts](../../com.aspose.slides/ifonts)

### getMajor() {#getMajor--}
```
public final IFonts getMajor()
```

슬라이드의 "heading" 부분에 대한 글꼴 컬렉션을 반환합니다. 읽기 전용 [IFonts](../../com.aspose.slides/ifonts).

**반환:**  
[IFonts](../../com.aspose.slides/ifonts)

### getName() {#getName--}
```
public final String getName()
```

글꼴 스키마 이름을 반환합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

글꼴 스키마 이름을 반환합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**  
com.aspose.slides.IDOMObject