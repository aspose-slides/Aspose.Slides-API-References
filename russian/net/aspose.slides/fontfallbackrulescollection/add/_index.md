---
title: Add
second_title: Справочник по API Aspose.Slides для .NET
description: Добавить указанное правило FallBack в конец коллекции.
type: docs
weight: 60
url: /ru/net/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection.Add method

Добавить указанное правило FallBack в конец коллекции.

```csharp
public void Add(IFontFallBackRule sourceRule)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceRule | IFontFallBackRule | Заданное правило для добавления |

### Примеры

```csharp
[C#]
using (Presentation pres = new Presentation ())
{
     //Получение пустой или предварительно инициализированной коллекции правил из FontsManager
    IFontFallBackRulesCollection rulesList = pres.FontsManager.FontFallBackRulesCollection;

     //Добавление нового правила в collection
    rulesList.Add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
}
```

### Смотрите также

* interface [IFontFallBackRule](../../ifontfallbackrule)
* class [FontFallBackRulesCollection](../../fontfallbackrulescollection)
* пространство имен [Aspose.Slides](../../fontfallbackrulescollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->