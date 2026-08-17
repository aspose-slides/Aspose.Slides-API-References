---
title: MasterThemeManager
second_title: Aspose.Slides для Java – справочник API
description: Обеспечивает доступ к основной теме презентации.
type: docs
url: /ru/com.aspose.slides/masterthememanager/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Все реализованные интерфейсы:**
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

Обеспечивает доступ к основной теме презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Возвращает объект переопределяющей темы. |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | Возвращает объект переопределяющей темы. |
| [createThemeEffective()](#createThemeEffective--) | Возвращает объект темы. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Определяет, переопределяет ли OverrideTheme унаследованную эффективную тему (Presentation.MasterTheme) или нет. |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | Определяет, переопределяет ли OverrideTheme унаследованную эффективную тему (Presentation.MasterTheme) или нет. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Применяет дополнительную цветовую схему к слайду. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```

Возвращает объект переопределяющей темы. Чтение/запись [IMasterTheme](../../com.aspose.slides/imastertheme).

**Возвращает:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```

Возвращает объект переопределяющей темы. Чтение/запись [IMasterTheme](../../com.aspose.slides/imastertheme).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |

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

Определяет, переопределяет ли OverrideTheme унаследованную эффективную тему (Presentation.MasterTheme) или нет. Чтение/запись boolean.

**Возвращает:**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```

Определяет, переопределяет ли OverrideTheme унаследованную эффективную тему (Presentation.MasterTheme) или нет. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Применяет дополнительную цветовую схему к слайду.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) объект. |