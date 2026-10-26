---
title: IOverrideTheme
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет переопределяемую тему.
type: docs
url: /ru/com.aspose.slides/ioverridetheme/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

Представляет переопределяемую тему.
## Методы

| Method | Description |
| --- | --- |
| [isEmpty()](#isEmpty--) | Истинное значение означает, что ColorScheme, FontScheme, FormatScheme равны null, и любое переопределение с помощью этого объекта темы отключено. |
| [initColorScheme()](#initColorScheme--) | Инициализировать ColorScheme новым объектом для переопределения ColorScheme у InheritedTheme. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | Инициализировать ColorScheme новым объектом для переопределения ColorScheme у InheritedTheme. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | Инициализировать ColorScheme новым объектом для переопределения ColorScheme у InheritedTheme. |
| [initFontScheme()](#initFontScheme--) | Инициализировать FontScheme новым объектом для переопределения FontScheme у InheritedTheme. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | Инициализировать FontScheme новым объектом для переопределения FontScheme у InheritedTheme. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | Инициализировать FontScheme новым объектом для переопределения FontScheme у InheritedTheme. |
| [initFormatScheme()](#initFormatScheme--) | Инициализировать FormatScheme новым объектом для переопределения FormatScheme у InheritedTheme. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | Инициализировать FormatScheme новым объектом для переопределения FormatScheme у InheritedTheme. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | Инициализировать FormatScheme новым объектом для переопределения FormatScheme у InheritedTheme. |
| [clear()](#clear--) | Установить ColorScheme, FontScheme, FormatScheme в null, чтобы отключить любое переопределение с помощью этого объекта темы. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

Истинное значение означает, что ColorScheme, FontScheme, FormatScheme равны null, и любое переопределение с помощью этого объекта темы отключено. **Только для чтения** boolean.

**Возвращает:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

Инициализировать ColorScheme новым объектом для переопределения ColorScheme у InheritedTheme.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

Инициализировать ColorScheme новым объектом для переопределения ColorScheme у InheritedTheme.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Данные для инициализации. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

Инициализировать ColorScheme новым объектом для переопределения ColorScheme у InheritedTheme. И инициализировать данные этого нового объекта данными ColorScheme у InheritedTheme.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

Инициализировать FontScheme новым объектом для переопределения FontScheme у InheritedTheme.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

Инициализировать FontScheme новым объектом для переопределения FontScheme у InheritedTheme.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Данные для инициализации. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

Инициализировать FontScheme новым объектом для переопределения FontScheme у InheritedTheme. И инициализировать данные этого нового объекта данными FontScheme у InheritedTheme.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

Инициализировать FormatScheme новым объектом для переопределения FormatScheme у InheritedTheme.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

Инициализировать FormatScheme новым объектом для переопределения FormatScheme у InheritedTheme.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Данные для инициализации. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

Инициализировать FormatScheme новым объектом для переопределения FormatScheme у InheritedTheme. И инициализировать данные этого нового объекта данными FormatScheme у InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```

Установить ColorScheme, FontScheme, FormatScheme в null, чтобы отключить любое переопределение с помощью этого объекта темы.