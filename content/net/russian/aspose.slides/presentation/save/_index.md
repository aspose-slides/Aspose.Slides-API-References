---
title: Save
second_title: Aspose.Sildes для .NET API Справочник
description: Сохраняет указанные слайды презентации в файл с указанным форматом с сохранением номеров страниц.
type: docs
weight: 380
url: /ru/aspose.slides/presentation/save/
---

## Save(string, int[], SaveFormat) {#save_7}

Сохраняет указанные слайды презентации в файл с указанным форматом с сохранением номеров страниц.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fname | String | Путь к созданному файлу. |
| slides | Int32[] | Массив с позициями слайдов, начиная с 1. |
| format | SaveFormat | Формат экспортируемых данных. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Когда параметр stream или slides равен null. |
| ArgumentOutOfRangeException | Когда параметр slides содержит неверные номера страниц. |
| InvalidOperationException | Когда используется неподдерживаемый SaveFormat, например, PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### См. Также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Сохраняет указанные слайды презентации в файл с указанным форматом с сохранением номеров страниц.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fname | String | Путь к созданному файлу. |
| slides | Int32[] | Массив с позициями слайдов, начиная с 1. |
| format | SaveFormat | Формат экспортируемых данных. |
| options | ISaveOptions | Дополнительные параметры формата. |

### См. Также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Сохраняет указанные слайды презентации в поток в указанном формате с сохранением номеров страниц.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Выходной поток. |
| slides | Int32[] | Массив с позициями слайдов, начиная с 1. |
| format | SaveFormat | Формат экспортируемых данных. |

### См. Также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Сохраняет указанные слайды презентации в поток в указанном формате с сохранением номеров страниц.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Выходной поток. |
| slides | Int32[] | Массив с позициями слайдов, начиная с 1. |
| format | SaveFormat | Формат экспортируемых данных. |
| options | ISaveOptions | Дополнительные параметры формата. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Когда параметр stream или slides равен null. |
| ArgumentOutOfRangeException | Когда параметр slides содержит неверные номера страниц. |
| InvalidOperationException | Когда используется неподдерживаемый SaveFormat, например, PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Примеры

Следующий пример показывает, как преобразовать PowerPoint в PNG.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail().Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

Следующий пример показывает, как преобразовать PowerPoint в PNG с пользовательскими размерами.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    float scaleX = 2f;
    float scaleY = 2f;
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail(scaleX, scaleY).Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

Следующий пример показывает, как преобразовать PowerPoint в PNG с заданным размером.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    Size size = new Size(960, 720);
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail(size).Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

### См. Также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat) {#save_5}

Сохраняет все слайды презентации в файл с указанным форматом.

```csharp
public void Save(string fname, SaveFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fname | String | Путь к созданному файлу. |
| format | SaveFormat | Формат экспортируемых данных. |

### См. Также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Сохраняет все слайды презентации в поток в указанном формате.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Выходной поток. |
| format | SaveFormat | Формат экспортируемых данных. |

### См. Также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### См. Также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Сохраняет все слайды презентации в поток в указанном формате и с дополнительными параметрами.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Выходной поток. |
| format | SaveFormat | Формат экспортируемых данных. |
| options | ISaveOptions | Дополнительные параметры формата. |

### Исключения

| исключение | условие |
| --- | --- |
| NotSupportedException | Если вы пытаетесь сохранить зашифрованный файл в формате, отличном от офисных 2007-2010 |

### См. Также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Сохраняет все слайды презентации в набор файлов, представляющих XAML-разметку.

```csharp
public void Save(IXamlOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | IXamlOptions | Параметры формата XAML. |

### Примеры

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### См. Также

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->