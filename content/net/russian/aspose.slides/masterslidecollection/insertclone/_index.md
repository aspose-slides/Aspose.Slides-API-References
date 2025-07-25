---
title: InsertClone
second_title: Aspose.Slides для .NET API Reference
description: Вставляет копию указанного мастер-слайда на указанную позицию в коллекции. Связанные макеты слайдов также будут скопированы.
type: docs
weight: 80
url: /ru/aspose.slides/masterslidecollection/insertclone/
---

## MasterSlideCollection.InsertClone метод

Вставляет копию указанного мастер-слайда на указанную позицию в коллекции. Связанные макеты слайдов также будут скопированы.

```csharp
public IMasterSlide InsertClone(int index, IMasterSlide sourceMaster)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс нового слайда. |
| sourceMaster | IMasterSlide | Слайд для клонирования. |

### Возвращаемое значение

Вставленный мастер-слайд.

### Примеры

Следующий пример показывает, как клонировать мастер-слайд в другую презентацию PowerPoint.

```csharp
[C#]
// Создайте экземпляр класса Presentation для загрузки файла исходной презентации
using (Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx"))
{
    // Создайте экземпляр класса Presentation для целевой презентации (куда слайд будет клонирован)
    using (Presentation destPres = new Presentation())
    {
        // Получите ISlide из коллекции слайдов в исходной презентации вместе с
        // Мастер-слайдом
        ISlide SourceSlide = srcPres.Slides[0];
        IMasterSlide SourceMaster = SourceSlide.LayoutSlide.MasterSlide;
		// Получите мастер-слайды целевой презентации
        IMasterSlideCollection masters = destPres.Masters;
        // Клонируйте нужный мастер-слайд из исходной презентации в коллекцию мастеров в
        // Целевой презентации
        IMasterSlide iSlide = masters.AddClone(SourceMaster);
        // Коллекция слайдов в целевой презентации
        ISlideCollection slds = destPres.Slides;
		// Клонируйте исходный слайд в коллекцию слайдов назначения.
        slds.AddClone(SourceSlide, iSlide, true);
        // Сохраните целевую презентацию на диск
        destPres.Save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
    }
}
```

### Смотрите также

* интерфейс [IMasterSlide](../../imasterslide)
* класс [MasterSlideCollection](../../masterslidecollection)
* пространство имен [Aspose.Slides](../../masterslidecollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->