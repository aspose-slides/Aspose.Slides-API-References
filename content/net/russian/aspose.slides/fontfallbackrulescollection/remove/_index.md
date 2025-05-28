---
title: Удалить
second_title: Справка по API Aspose.Slides для .NET
description: Удаляет первое вхождение конкретного правила FallBack из коллекции.
type: docs
weight: 90
url: /ru/aspose.slides/fontfallbackrulescollection/remove/
---

## FontFallBackRulesCollection.Remove метод

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

### См. Также

* интерфейс [IFontFallBackRule](../../ifontfallbackrule)
* класс [FontFallBackRulesCollection](../../fontfallbackrulescollection)
* пространство имен [Aspose.Slides](../../fontfallbackrulescollection)
* сборка [Aspose.Slides](../../../)

<!-- ДО НЕ ТРАТИ ВРЕМЯ: сгенерировано xmldocmd для Aspose.Slides.dll -->