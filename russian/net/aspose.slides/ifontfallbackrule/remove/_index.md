---
title: Remove
second_title: Справочник по API Aspose.Slides для .NET
description: Удаляет первое вхождение определенного шрифта FallBack из списка.
type: docs
weight: 80
url: /ru/net/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule.Remove method

Удаляет первое вхождение определенного шрифта FallBack из списка.

```csharp
public void Remove(string fontName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | String | Имя шрифта для удаления из списка. |

### Примеры

```csharp
[C#]
 // Создать правило, содержащее список шрифтов.
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");

 //Удаление Tahoma из list
newRule.Remove ("Tahoma");
```

### Смотрите также

* interface [IFontFallBackRule](../../ifontfallbackrule)
* пространство имен [Aspose.Slides](../../ifontfallbackrule)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->