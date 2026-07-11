---
title: BaseOverrideThemeManager
second_title: Aspose.Slides для Android через справочник Java API
description: Базовый класс для классов, предоставляющих доступ к различным типам переопределённых тем.
type: docs
url: /ru/com.aspose.slides/baseoverridethememanager/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Все реализованные интерфейсы:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

Базовый класс для классов, предоставляющих доступ к различным типам переопределённых тем.
## Методы

| Метод | Описание |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Returns the overriding theme object. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Returns the overriding theme object. |
| [createThemeEffective()](#createThemeEffective--) | Returns the theme object. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Determines whether OverrideTheme overrides inherited effective theme or not. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Applies extra color scheme to a slide. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```


Returns the overriding theme object. Read/write [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Возвращаемое значение:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```


Returns the overriding theme object. Read/write [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


Returns the theme object.

**Возвращаемое значение:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```


Determines whether OverrideTheme overrides inherited effective theme or not. To enable OverrideTheme for overriding use OverrideTheme.Init\*() methods. To disable OverrideTheme from overriding use OverrideTheme.Clear() method. Read-only boolean.

**Возвращаемое значение:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```


Applies extra color scheme to a slide.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | The [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) object. |