---
title: IOverrideTheme
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 오버라이딩 테마를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ioverridetheme/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

오버라이딩 테마를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isEmpty()](#isEmpty--) | True 값은 ColorScheme, FontScheme, FormatScheme이 null이고 이 테마 객체로의 모든 오버라이딩이 비활성화됨을 의미합니다. |
| [initColorScheme()](#initColorScheme--) | InheritedTheme의 ColorScheme을 오버라이드하기 위해 새 객체로 ColorScheme을 초기화합니다. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | InheritedTheme의 ColorScheme을 오버라이드하기 위해 새 객체로 ColorScheme을 초기화합니다. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | InheritedTheme의 ColorScheme을 오버라이드하기 위해 새 객체로 ColorScheme을 초기화합니다. |
| [initFontScheme()](#initFontScheme--) | InheritedTheme의 FontScheme을 오버라이드하기 위해 새 객체로 FontScheme을 초기화합니다. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | InheritedTheme의 FontScheme을 오버라이드하기 위해 새 객체로 FontScheme을 초기화합니다. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | InheritedTheme의 FontScheme을 오버라이드하기 위해 새 객체로 FontScheme을 초기화합니다. |
| [initFormatScheme()](#initFormatScheme--) | InheritedTheme의 FormatScheme을 오버라이드하기 위해 새 객체로 FormatScheme을 초기화합니다. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | InheritedTheme의 FormatScheme을 오버라이드하기 위해 새 객체로 FormatScheme을 초기화합니다. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | InheritedTheme의 FormatScheme을 오버라이드하기 위해 새 객체로 FormatScheme을 초기화합니다. |
| [clear()](#clear--) | ColorScheme, FontScheme, FormatScheme을 null로 설정하여 이 테마 객체로의 모든 오버라이딩을 비활성화합니다. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

True 값은 ColorScheme, FontScheme, FormatScheme이 null이고 이 테마 객체로의 모든 오버라이딩이 비활성화됨을 의미합니다. 읽기 전용 boolean.

**반환:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

InheritedTheme의 ColorScheme을 오버라이드하기 위해 새 객체로 ColorScheme을 초기화합니다.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

InheritedTheme의 ColorScheme을 오버라이드하기 위해 새 객체로 ColorScheme을 초기화합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | 초기화에 사용할 데이터. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

InheritedTheme의 ColorScheme을 오버라이드하기 위해 새 객체로 ColorScheme을 초기화합니다. 그리고 이 새 객체의 데이터를 InheritedTheme의 ColorScheme 데이터로 초기화합니다.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

InheritedTheme의 FontScheme을 오버라이드하기 위해 새 객체로 FontScheme을 초기화합니다.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

InheritedTheme의 FontScheme을 오버라이드하기 위해 새 객체로 FontScheme을 초기화합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | 초기화에 사용할 데이터. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

InheritedTheme의 FontScheme을 오버라이드하기 위해 새 객체로 FontScheme을 초기화합니다. 그리고 이 새 객체의 데이터를 InheritedTheme의 FontScheme 데이터로 초기화합니다.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

InheritedTheme의 FormatScheme을 오버라이드하기 위해 새 객체로 FormatScheme을 초기화합니다.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

InheritedTheme의 FormatScheme을 오버라이드하기 위해 새 객체로 FormatScheme을 초기화합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | 초기화에 사용할 데이터. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

InheritedTheme의 FormatScheme을 오버라이드하기 위해 새 객체로 FormatScheme을 초기화합니다. 그리고 이 새 객체의 데이터를 InheritedTheme의 FormatScheme 데이터로 초기화합니다.

### clear() {#clear--}
```
public abstract void clear()
```

ColorScheme, FontScheme, FormatScheme을 null로 설정하여 이 테마 객체로의 모든 오버라이딩을 비활성화합니다.