---
title: BaseOverrideThemeManager
second_title: Справочник по API Aspose.Slides для .NET
description: Базовый класс для классов предоставляющих доступ к различным типам переопределенных тем.
type: docs
weight: 10230
url: /ru/net/aspose.slides.theme/baseoverridethememanager/
---
## BaseOverrideThemeManager class

Базовый класс для классов, предоставляющих доступ к различным типам переопределенных тем.

```csharp
public abstract class BaseOverrideThemeManager : BaseThemeManager, IOverrideThemeManager
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [IsOverrideThemeEnabled](../../aspose.slides.theme/baseoverridethememanager/isoverridethemeenabled) { get; } | Определяет, переопределяет ли OverrideTheme унаследованную действующую тему или нет. Чтобы включить OverrideTheme для переопределения, используйте методы OverrideTheme.Init*(). Чтобы отключить OverrideTheme от переопределения, используйте метод OverrideTheme.Clear(). Только чтениеBoolean. |
| [OverrideTheme](../../aspose.slides.theme/baseoverridethememanager/overridetheme) { get; set; } | Возвращает основной объект темы. Чтение/запись[`IOverrideTheme`](../ioverridetheme). |

## Методы

| Имя | Описание |
| --- | --- |
| [ApplyColorScheme](../../aspose.slides.theme/baseoverridethememanager/applycolorscheme)(IExtraColorScheme) | Применяет к слайду дополнительную цветовую схему. |
| [CreateThemeEffective](../../aspose.slides.theme/baseoverridethememanager/createthemeeffective)() | Возвращает объект темы. |

### Смотрите также

* class [BaseThemeManager](../basethememanager)
* interface [IOverrideThemeManager](../ioverridethememanager)
* пространство имен [Aspose.Slides.Theme](../../aspose.slides.theme)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->