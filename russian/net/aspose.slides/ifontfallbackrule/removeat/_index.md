---
title: RemoveAt
second_title: Справочник по API Aspose.Slides для .NET
description: Удаляет шрифт FallBack по указанному индексу списка.
type: docs
weight: 90
url: /ru/net/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule.RemoveAt method

Удаляет шрифт FallBack по указанному индексу списка.

```csharp
public void RemoveAt(int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Начинающийся с нуля индекс шрифта для удалять. |

### Примеры

```csharp
[C#]
 // Создать правило, содержащее список шрифтов.
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");

 //Удаление Tahoma из list
newRule.Remove (2);
```

### Смотрите также

* interface [IFontFallBackRule](../../ifontfallbackrule)
* пространство имен [Aspose.Slides](../../ifontfallbackrule)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->