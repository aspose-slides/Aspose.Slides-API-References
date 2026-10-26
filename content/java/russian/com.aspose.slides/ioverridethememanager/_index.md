---
title: IOverrideThemeManager
second_title: Справочник API Aspose.Slides для Java
description: Обеспечивает доступ к различным типам переопределённых тем.
type: docs
url: /ru/com.aspose.slides/ioverridethememanager/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

Обеспечивает доступ к различным типам переопределённых тем.
## Методы

| Метод | Описание |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Определяет, переопределяет ли OverrideTheme унаследованную эффективную тему или нет. |
| [getOverrideTheme()](#getOverrideTheme--) | Возвращает объект переопределяющей темы. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Возвращает объект переопределяющей темы. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```


Определяет, переопределяет ли OverrideTheme унаследованную эффективную тему или нет. Чтобы включить OverrideTheme для переопределения, используйте методы OverrideTheme.Init*(). Чтобы отключить OverrideTheme от переопределения, используйте метод OverrideTheme.Clear(). Только для чтения boolean.

**Возвращает:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```


Возвращает объект переопределяющей темы. Чтение/запись [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Возвращает:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```


Возвращает объект переопределяющей темы. Чтение/запись [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |