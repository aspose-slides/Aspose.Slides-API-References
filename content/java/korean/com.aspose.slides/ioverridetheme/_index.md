---
title: IOverrideTheme
second_title: Aspose.Slides for Java API 레퍼런스
description: 재정의된 테마를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ioverridetheme/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

재정의된 테마를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isEmpty()](#isEmpty--) | True 값은 ColorScheme, FontScheme, FormatScheme이 null이며 이 테마 객체에 대한 모든 재정의가 비활성화됨을 의미합니다. |
| [initColorScheme()](#initColorScheme--) | 새 객체로 ColorScheme을 초기화하여 InheritedTheme의 ColorScheme을 재정의합니다. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | 새 객체로 ColorScheme을 초기화하여 InheritedTheme의 ColorScheme을 재정의합니다. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | 새 객체로 ColorScheme을 초기화하여 InheritedTheme의 ColorScheme을 재정의합니다. |
| [initFontScheme()](#initFontScheme--) | 새 객체로 FontScheme을 초기화하여 InheritedTheme의 FontScheme을 재정의합니다. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | 새 객체로 FontScheme을 초기화하여 InheritedTheme의 FontScheme을 재정의합니다. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | 새 객체로 FontScheme을 초기화하여 InheritedTheme의 FontScheme을 재정의합니다. |
| [initFormatScheme()](#initFormatScheme--) | 새 객체로 FormatScheme을 초기화하여 InheritedTheme의 FormatScheme을 재정의합니다. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | 새 객체로 FormatScheme을 초기화하여 InheritedTheme의 FormatScheme을 재정의합니다. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | 새 객체로 FormatScheme을 초기화하여 InheritedTheme의 FormatScheme을 재정의합니다. |
| [clear()](#clear--) | ColorScheme, FontScheme, FormatScheme을 null로 설정하여 이 테마 객체에 대한 모든 재정의를 비활성화합니다. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```


True 값은 ColorScheme, FontScheme, FormatScheme이 null이며 이 테마 객체에 대한 모든 재정의가 비활성화됨을 의미합니다. 읽기 전용 boolean.

**반환:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```


새 객체로 ColorScheme을 초기화하여 InheritedTheme의 ColorScheme을 재정의합니다.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```


새 객체로 ColorScheme을 초기화하여 InheritedTheme의 ColorScheme을 재정의합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | 초기화에 사용할 데이터. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```


새 객체로 ColorScheme을 초기화하여 InheritedTheme의 ColorScheme을 재정의합니다. 그리고 이 새 객체의 데이터를 InheritedTheme의 ColorScheme 데이터로 초기화합니다.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```


새 객체로 FontScheme을 초기화하여 InheritedTheme의 FontScheme을 재정의합니다.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```


새 객체로 FontScheme을 초기화하여 InheritedTheme의 FontScheme을 재정의합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | 초기화에 사용할 데이터. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```


새 객체로 FontScheme을 초기화하여 InheritedTheme의 FontScheme을 재정의합니다. 그리고 이 새 객체의 데이터를 InheritedTheme의 FontScheme 데이터로 초기화합니다.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```


새 객체로 FormatScheme을 초기화하여 InheritedTheme의 FormatScheme을 재정의합니다.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```


새 객체로 FormatScheme을 초기화하여 InheritedTheme의 FormatScheme을 재정의합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | 초기화에 사용할 데이터. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```


새 객체로 FormatScheme을 초기화하여 InheritedTheme의 FormatScheme을 재정의합니다. 그리고 이 새 객체의 데이터를 InheritedTheme의 FormatScheme 데이터로 초기화합니다.

### clear() {#clear--}
```
public abstract void clear()
```


ColorScheme, FontScheme, FormatScheme을 null로 설정하여 이 테마 객체에 대한 모든 재정의를 비활성화합니다.