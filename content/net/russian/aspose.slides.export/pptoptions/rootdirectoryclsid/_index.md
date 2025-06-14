---
title: RootDirectoryClsid
second_title: Aspose.Sildes для .NET API Справочник
description: Представляет объектный класс GUID CLSID, который хранится в записи корневого каталога. Может быть использован для активации приложения документов через COM. Значение по умолчанию - 64818D11-4F9B-11CF-86EA-00AA00B929E8, соответствующее Microsoft Powerpoint.Slide.8.
type: docs
weight: 20
url: /ru/aspose.slides.export/pptoptions/rootdirectoryclsid/
---

## PptOptions.RootDirectoryClsid свойство

Представляет объектный класс GUID (CLSID), который хранится в записи корневого каталога. Может быть использован для активации приложения документа через COM. Значение по умолчанию - '64818D11-4F9B-11CF-86EA-00AA00B929E8', соответствующее 'Microsoft Powerpoint.Slide.8'.

```csharp
public Guid RootDirectoryClsid { get; set; }
```

### Примеры

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    PptOptions pptOptions = new PptOptions();
    
    /// установить CLSID на 'Microsoft Powerpoint.Show.8'
    pptOptions.RootDirectoryClsid = new Guid("64818D10-4F9B-11CF-86EA-00AA00B929E8");
    
    pres.Save("pres.ppt", SaveFormat.Ppt, pptOptions);
}
```

### См. также

* класс [PptOptions](../../pptoptions)
* пространство имен [Aspose.Slides.Export](../../pptoptions)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->