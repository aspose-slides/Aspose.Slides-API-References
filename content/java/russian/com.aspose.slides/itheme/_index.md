---
title: ITheme
second_title: Aspose.Slides для Java API Reference
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

| Метод | Описание |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Возвращает схему цветов. |
| [getFontScheme()](#getFontScheme--) | Возвращает схему шрифтов. |
| [getFormatScheme()](#getFormatScheme--) | Возвращает схему формата фигур. |
| [getEffective()](#getEffective--) | Получает эффективные данные темы с применённым наследованием. |
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

Возвращает схему формата фигур. Только для чтения [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Возвращаемое значение:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```

Получает эффективные данные темы с применённым наследованием.

**Возвращаемое значение:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - A [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).