---
title: DeleteEmbeddedBinaryObjects
second_title: Aspose.Sildes для .NET API Reference
description: Определяет, удалит ли Aspose.Slides все встроенные бинарные объекты при загрузке презентации.
type: docs
weight: 60
url: /ru/aspose.slides/iloadoptions/deleteembeddedbinaryobjects/
---

## ILoadOptions.DeleteEmbeddedBinaryObjects свойство

Определяет, удалит ли Aspose.Slides все встроенные бинарные объекты при загрузке презентации.

Типы встроенных бинарных объектов:

* VBA Project [`VbaProject`](../../ipresentation/vbaproject)
* OLE Object встроенные данные [`EmbeddedFileData`](../../ioleembeddeddatainfo/embeddedfiledata)
* ActiveX Control бинарные данные [`ActiveXControlBinary`](../../icontrol/activexcontrolbinary)

Читабельный/записываемый логический тип.

```csharp
public bool DeleteEmbeddedBinaryObjects { get; set; }
```

### Примечания

По умолчанию **false**.

### Примеры

Следующий пример показывает, как загрузить презентацию без любых встроенных бинарных объектов.

```csharp
[C#]
LoadOptions loadOptions = new LoadOptions();
loadOptions.DeleteEmbeddedBinaryObjects = true;
using (Presentation pres = new Presentation("pres.ppt", loadOptions))
{
    pres.Save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
}
```

### См. также

* интерфейс [ILoadOptions](../../iloadoptions)
* пространство имен [Aspose.Slides](../../iloadoptions)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->