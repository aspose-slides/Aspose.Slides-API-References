---
title: FindAndReplaceText
second_title: Aspose.Slides для .NET API Reference
description: Находит и заменяет текст в презентации с заданным форматом
type: docs
weight: 20
url: /ru/aspose.slides.util/slideutil/findandreplacetext/
---

## SlideUtil.FindAndReplaceText метод

Находит и заменяет текст в презентации с заданным форматом

```csharp
public static void FindAndReplaceText(IPresentation presentation, bool withMasters, string find, 
    string replace, PortionFormat format = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| presentation | IPresentation | Просматриваемая презентация. |
| withMasters | Boolean | Определяет, следует ли просматривать мастер-слайды. |
| find | String | Строковое значение для поиска. |
| replace | String | Строковое значение для замены. |
| format | PortionFormat | Формат для замены текстовой части. Если null, будет использован формат первого символа найденной строки |

### Примеры

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    PortionFormat format = new PortionFormat
    {
        FontHeight = 24f,
        FontItalic = NullableBool.True,
        FillFormat =
        {
            FillType = FillType.Solid,
            SolidFillColor =
            {
                Color = Color.Red
            }
        }
    };
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(pres, true, "[this block] ", "my text ", format);
    pres.Save("replaced", SaveFormat.Pptx);
}
```

### См. также

* интерфейс [IPresentation](../../../aspose.slides/ipresentation)
* класс [PortionFormat](../../../aspose.slides/portionformat)
* класс [SlideUtil](../../slideutil)
* пространство имен [Aspose.Slides.Util](../../slideutil)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->