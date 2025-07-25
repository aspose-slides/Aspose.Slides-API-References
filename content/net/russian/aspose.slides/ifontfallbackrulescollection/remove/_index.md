---
title: Remove
second_title: Aspose.Sildes для .NET API Reference
description: Удаляет первое вхождение конкретного правила FallBack из коллекции.
type: docs
weight: 30
url: /ru/aspose.slides/ifontfallbackrulescollection/remove/
---

## IFontFallBackRulesCollection.Remove метод

Удаляет первое вхождение конкретного правила FallBack из коллекции.

```csharp
public void Remove(IFontFallBackRule targetRule)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| targetRule | IFontFallBackRule | Правило для удаления из коллекции. |

### Примеры

```csharp
[C#]
using (Presentation pres = new Presentation ())
{
    //Получение пустой или предварительно инициализированной коллекции правил из FontsManager
    IFontFallBackRulesCollection rulesList = pres.FontsManager.FontFallBackRulesCollection;

    //Добавление нескольких правил в коллекцию
    rulesList.Add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
    rulesList.Add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));

    //Получение объекта первого правила в коллекции
    IFontFallBackRule firstRule = rulesList[0];
    //Удаление 
    rulesList.Remove (firstRule);
}
```

### Также см.

* интерфейс [IFontFallBackRule](../../ifontfallbackrule)
* интерфейс [IFontFallBackRulesCollection](../../ifontfallbackrulescollection)
* пространство имен [Aspose.Slides](../../ifontfallbackrulescollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->