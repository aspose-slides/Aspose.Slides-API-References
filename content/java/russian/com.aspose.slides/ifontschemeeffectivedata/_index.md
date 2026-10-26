---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Неизменяемый объект, содержащий эффективные свойства схемы шрифтов.
type: docs
url: /ru/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

Неизменяемый объект, содержащий эффективные свойства схемы шрифтов.

--------------------

Этот интерфейс используется как часть [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## Методы

| Метод | Описание |
| --- | --- |
| [getMinor()](#getMinor--) | Returns the fonts collection for a "body" part of the slide. |
| [getMajor()](#getMajor--) | Returns the fonts collection for a "heading" part of the slide. |
| [getName()](#getName--) | Returns the font scheme name. |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```

Возвращает коллекцию шрифтов для части слайда "body". Только для чтения [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Returns:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```

Возвращает коллекцию шрифтов для части слайда "heading". Только для чтения [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Returns:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```

Возвращает имя схемы шрифтов. Только для чтения String.

**Returns:**
java.lang.String