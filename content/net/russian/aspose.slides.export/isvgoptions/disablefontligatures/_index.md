---
title: DisableFontLigatures
second_title: Aspose.Slides для .NET API Справочник
description: Получает или устанавливает значение, указывающее, будет ли текст отображаться без использования лигатур. Когда установлено значение true, лигатуры будут отключены в выходном отображении. По умолчанию это свойство установлено в false.
type: docs
weight: 40
url: /ru/aspose.slides.export/isvgoptions/disablefontligatures/
---

## Свойство ISVGOptions.DisableFontLigatures

Получает или устанавливает значение, указывающее, будет ли текст отображаться без использования лигатур. Когда установлено значение `true`, лигатуры будут отключены в выходном отображении. По умолчанию это свойство установлено в `false`.

```csharp
public bool DisableFontLigatures { get; set; }
```

### Примеры

Пример:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    SVGOptions options = new SVFOptions
    {
        DisableFontLigatures = true // Отключить лигатуры в отображении текста
    };
    
    using (FileStream fileStream = new FileStream("slide-0.svg", FileMode.Create, FileAccess.Write))
    {
        pres.Slides[0].WriteAsSvg(fileStream);   
    }
}
```

### См. Также

* интерфейс [ISVGOptions](../../isvgoptions)
* пространство имен [Aspose.Slides.Export](../../isvgoptions)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->