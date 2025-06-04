---
title: RemoveAt
second_title: Aspose.Slidеs для .NET API Справочник
description: Удаляет шрифт FallBack по указанному индексу в списке.
type: docs
weight: 100
url: /ru/aspose.slides/fontfallbackrule/removeat/
---

## FontFallBackRule.RemoveAt метод

Удаляет шрифт FallBack по указанному индексу в списке.

```csharp
public void RemoveAt(int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс шрифта для удаления, начинающийся с нуля. |

### Примеры

```csharp
[C#]
// Создание правила, содержащее список шрифтов.
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");

//Удаление Tahoma из списка.
newRule.Remove (2);
```

### См. также

* класс [FontFallBackRule](../../fontfallbackrule)
* пространство имен [Aspose.Slides](../../fontfallbackrule)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->