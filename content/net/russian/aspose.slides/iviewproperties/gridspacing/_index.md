---
title: GridSpacing
second_title: Aspose.Slides для .NET API Справочник
description: Возвращает или устанавливает расстояние сетки, которое должно использоваться для сетки, лежащей в основе документа презентации, в пунктах. Чтение/запись Single.
type: docs
weight: 10
url: /ru/aspose.slides/iviewproperties/gridspacing/
---

## Свойство IViewProperties.GridSpacing

Возвращает или устанавливает расстояние сетки, которое должно использоваться для сетки, лежащей в основе документа презентации, в пунктах. Чтение/запись Single.

```csharp
public float GridSpacing { get; set; }
```

### Примечания

Значение расстояния сетки должно быть положительным числом. Типичный диапазон значений составляет от 1 мм (2.8349607 пункта) до 2 дюймов (144 пункта).

### Примеры

Следующий образец кода показывает, как изменить расстояние сетки в презентации PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    pres.ViewProperties.GridSpacing = 72f;
    pres.Save("GridSpacing_out.pptx", SaveFormat.Pptx);
}
```

### См. также

* интерфейс [IViewProperties](../../iviewproperties)
* пространство имен [Aspose.Slides](../../iviewproperties)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->