---
title: ITheme
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет тему.
type: docs
url: /ru/com.aspose.slides/itheme/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

Представляет тему.
## Методы

| Method | Description |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Возвращает схему цветов. |
| [getFontScheme()](#getFontScheme--) | Возвращает схему шрифтов. |
| [getFormatScheme()](#getFormatScheme--) | Возвращает схему форматов фигур. |
| [getEffective()](#getEffective--) | Получает фактические данные темы с применённым наследованием. |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

Возвращает схему цветов. Только для чтения [IColorScheme](../../com.aspose.slides/icolorscheme).

**Возвращаемое значение:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

Возвращает схему шрифтов. Только для чтения [IFontScheme](../../com.aspose.slides/ifontscheme).

**Возвращаемое значение:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

Возвращает схему форматов фигур. Только для чтения [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Возвращаемое значение:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```

Получает фактические данные темы с применённым наследованием.

**Возвращаемое значение:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).