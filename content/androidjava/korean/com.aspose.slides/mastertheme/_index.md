---
title: MasterTheme
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 마스터 테마를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/mastertheme/
---
**상속:**  
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

마스터 테마를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | 색 구성표를 반환합니다. |
| [getFontScheme()](#getFontScheme--) | 글꼴 구성표를 반환합니다. |
| [getFormatScheme()](#getFormatScheme--) | 모양 형식 구성표를 반환합니다. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | 추가 색 구성표 컬렉션을 반환합니다. |
| [getName()](#getName--) | 테마 이름을 반환합니다. |
| [setName(String value)](#setName-java.lang.String-) | 테마 이름을 반환합니다. |
| [getVersion()](#getVersion--) |  |

### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```

색 구성표를 반환합니다. 읽기 전용 [IColorScheme](../../com.aspose.slides/icolorscheme).

**반환값:**  
[IColorScheme](../../com.aspose.slides/icolorscheme)

### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```

글꼴 구성표를 반환합니다. 읽기 전용 [IFontScheme](../../com.aspose.slides/ifontscheme).

**반환값:**  
[IFontScheme](../../com.aspose.slides/ifontscheme)

### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```

모양 형식 구성표를 반환합니다. 읽기 전용 [IFormatScheme](../../com.aspose.slides/iformatscheme).

**반환값:**  
[IFormatScheme](../../com.aspose.slides/iformatscheme)

### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```

추가 색 구성표 컬렉션을 반환합니다. 이 구성표는 프레젠테이션의 모양에 영향을 주지 않으며 슬라이드의 기본 색 구성표로 선택될 수 있습니다. 읽기 전용 [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**반환값:**  
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)

### getName() {#getName--}
```
public final String getName()
```

테마 이름을 반환합니다. 읽기/쓰기 String.

**반환값:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

테마 이름을 반환합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환값:**  
long