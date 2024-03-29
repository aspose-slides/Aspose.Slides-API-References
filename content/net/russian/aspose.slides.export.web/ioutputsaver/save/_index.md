---
title: Save
second_title: Справочник по API Aspose.Slides для .NET
description: Сохраняет выходной файл по указанному пути.
type: docs
weight: 10
url: /ru/aspose.slides.export.web/ioutputsaver/save/
---
## IOutputSaver.Save method

Сохраняет выходной файл по указанному пути.

```csharp
public void Save(string path, IOutputFile outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | String | Путь для сохранения файла. |
| outputFile | IOutputFile | Выходной файл. |

### Примеры

Сохранение вFileStreamпример реализации:

```csharp
[C#]
public void Save(string path, IOutputFile outputFile)
{
    using (FileStream stream = new FileStream(path, FileMode.Create))
    {
        outputFile.Write(stream);
    }
}
```

### Смотрите также

* interface [IOutputFile](../../ioutputfile)
* interface [IOutputSaver](../../ioutputsaver)
* пространство имен [Aspose.Slides.Export.Web](../../ioutputsaver)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
