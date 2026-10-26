---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective font scheme properties.
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
| [getMinor()](#getMinor--) | Возвращает коллекцию шрифтов для части слайда "body". |
| [getMajor()](#getMajor--) | Возвращает коллекцию шрифтов для части слайда "heading". |
| [getName()](#getName--) | Возвращает название схемы шрифтов. |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```


Возвращает коллекцию шрифтов для части слайда "body". Только для чтения [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Возвращает:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```


Возвращает коллекцию шрифтов для части слайда "heading". Только для чтения [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Возвращает:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```


Возвращает название схемы шрифтов. Только для чтения String.

**Возвращает:**
java.lang.String