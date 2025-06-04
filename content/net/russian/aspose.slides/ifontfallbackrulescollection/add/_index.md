---
title: Add
second_title: Aspose.Sildes для .NET API Справочник
description: Добавить новое правило FallBack в конец коллекции.
type: docs
weight: 20
url: /ru/aspose.slides/ifontfallbackrulescollection/add/
---

## IFontFallBackRulesCollection.Add метод

Добавить новое правило FallBack в конец коллекции.

```csharp
public void Add(IFontFallBackRule sourceRule)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceRule | IFontFallBackRule | Указанное правило для добавления |

### Примеры

```csharp
[C#]
using (Presentation pres = new Presentation ())
{
    //Получение пустой или предварительно инициализированной коллекции правил из FontsManager
    IFontFallBackRulesCollection rulesList = pres.FontsManager.FontFallBackRulesCollection;

    //Добавление нового правила в коллекцию
    rulesList.Add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
}
```

### См. также

* интерфейс [IFontFallBackRule](../../ifontfallbackrule)
* интерфейс [IFontFallBackRulesCollection](../../ifontfallbackrulescollection)
* пространство имен [Aspose.Slides](../../ifontfallbackrulescollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->