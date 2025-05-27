---
title: SetEmbeddedData
second_title: Справочник по API Aspose.Sildes для .NET
description: Устанавливает информацию о встроенных данных OLE. Этот метод изменяет свойства объекта, чтобы отразить новые данные, и устанавливает флаг IsObjectLink в значение false, указывая на то, что OLE-объект встроен.
type: docs
weight: 150
url: /ru/aspose.slides/oleobjectframe/setembeddeddata/
---

## OleObjectFrame.SetEmbeddedData метод

Устанавливает информацию о встроенных данных OLE. Этот метод изменяет свойства объекта, чтобы отразить новые данные, и устанавливает флаг IsObjectLink в значение false, указывая на то, что OLE-объект встроен.

```csharp
public void SetEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| embeddedData | IOleEmbeddedDataInfo | Встроенные данные [`IOleEmbeddedDataInfo`](../../ioleembeddeddatainfo) |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Когда параметр embeddedData равен null. |

### Примеры

```csharp
[C#]
using (Presentation pres = new Presentation("SomePresentation.pptx"))
{
    OleObjectFrame oof = pres.Slides[0].Shapes[0] as OleObjectFrame;
    if (oof != null)
    {
        IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(File.ReadAllBytes("Picture.png"), "png");
        oof.SetEmbeddedData(newData);
    }
}
```

### См. Также

* интерфейс [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo)
* класс [OleObjectFrame](../../oleobjectframe)
* пространство имен [Aspose.Slides](../../oleobjectframe)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->