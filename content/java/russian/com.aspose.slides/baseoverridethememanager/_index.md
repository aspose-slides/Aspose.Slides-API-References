---
title: BaseOverrideThemeManager
second_title: Справочник API Aspose.Slides для Java
description: Базовый класс для классов, предоставляющих доступ к различным типам переопределённых тем.
type: docs
url: /ru/com.aspose.slides/baseoverridethememanager/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**All Implemented Interfaces:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

Базовый класс для классов, предоставляющих доступ к различным типам переопределённых тем.
## Методы

| Метод | Описание |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Возвращает объект переопределяющей темы. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Возвращает объект переопределяющей темы. |
| [createThemeEffective()](#createThemeEffective--) | Возвращает объект темы. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Определяет, переопределяет ли OverrideTheme унаследованную эффективную тему или нет. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Применяет дополнительную цветовую схему к слайду. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

Возвращает объект переопределяющей темы. Чтение/запись [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Возвращает:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

Возвращает объект переопределяющей темы. Чтение/запись [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Возвращает объект темы.

**Возвращает:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

Определяет, переопределяет ли OverrideTheme унаследованную эффективную тему или нет. Чтобы включить переопределение OverrideTheme, используйте методы OverrideTheme.Init*(). Чтобы отключить переопределение OverrideTheme, используйте метод OverrideTheme.Clear(). Только для чтения boolean.

**Возвращает:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Применяет дополнительную цветовую схему к слайду.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | Объект [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme). |