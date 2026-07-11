---
title: IThemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Неизменяемый объект, содержащий эффективные свойства темы.
type: docs
url: /ru/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Неизменяемый объект, содержащий эффективные свойства темы.

--------------------

Этот интерфейс используется вместе с интерфейсом [ITheme](../../com.aspose.slides/itheme) для получения эффективных значений форматирования с учётом наследования.
## Методы

| Метод | Описание |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | Возвращает цветовую схему. |
| [getFontScheme()](#getFontScheme--) | Возвращает схему шрифтов. |
| [getFormatScheme()](#getFormatScheme--) | Возвращает схему формата фигур. |
### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```


Возвращает цветовую схему.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| styleColor | java.lang.Integer | Цвет java.lang.Integer |

**Возвращает:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - цветовая схема [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```


Возвращает схему шрифтов. Только для чтения [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Возвращает:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```


Возвращает схему формата фигур. Только для чтения [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Возвращает:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)