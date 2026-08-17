---
title: IThemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Неизменяемый объект, содержащий эффективные свойства темы.
type: docs
url: /ru/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Неизменяемый объект, содержащий эффективные свойства темы.

--------------------

Этот интерфейс используется вместе с интерфейсом [ITheme](../../com.aspose.slides/itheme) для возврата эффективных значений форматирования с применённым наследованием.
## Методы

| Метод | Описание |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | Возвращает схему цветов. |
| [getFontScheme()](#getFontScheme--) | Возвращает схему шрифтов. |
| [getFormatScheme()](#getFormatScheme--) | Возвращает схему форматов фигур. |
### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```


Возвращает схему цветов.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Возвращаемое значение:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - схема цветов [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```


Возвращает схему шрифтов. Только для чтения [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Возвращаемое значение:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```


Возвращает схему форматов фигур. Только для чтения [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Возвращаемое значение:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)