---
title: Save
second_title: Aspose.Sildes для .NET — справка API
description: Сохраняет все слайды презентации в файл в указанном формате.
type: docs
weight: 400
url: /ru/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

Сохраняет все слайды презентации в файл в указанном формате.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | Путь к создаваемому файлу. |
| format | SaveFormat | Формат экспортируемых данных. |

### См. также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* класс [Presentation](../../presentation)
* пространство имён [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Сохраняет все слайды презентации в поток в указанном формате.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Выходной поток. |
| format | SaveFormat | Формат экспортируемых данных. |

### См. также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* класс [Presentation](../../presentation)
* пространство имён [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### См. также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* интерфейс [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* класс [Presentation](../../presentation)
* пространство имён [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Сохраняет все слайды презентации в поток в указанном формате и с дополнительными параметрами.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Выходной поток. |
| format | SaveFormat | Формат экспортируемых данных. |
| options | ISaveOptions | Дополнительные параметры формата. |

### Исключения

| exception | condition |
| --- | --- |
| NotSupportedException | Если попытаться сохранить зашифрованный файл в формате, отличном от Office 2007-2010 |

### См. также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* интерфейс [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* класс [Presentation](../../presentation)
* пространство имён [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Сохраняет все слайды презентации в набор файлов, представляющих разметку XAML.

```csharp
public void Save(IXamlOptions options)
```

| Parameter | Type | Description |
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

### См. также

* интерфейс [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* класс [Presentation](../../presentation)
* пространство имён [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Сохраняет указанные слайды презентации в файл в указанном формате, сохраняя номера страниц.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | Путь к создаваемому файлу. |
| slides | Int32[] | Массив номеров слайдов, начиная с 1. |
| format | SaveFormat | Формат экспортируемых данных. |

### Исключения

| exception | condition |
| --- | --- |
| ArgumentNullException | Когда параметр stream или slides имеет значение null. |
| ArgumentOutOfRangeException | Когда массив slides содержит некорректные номера страниц. |
| InvalidOperationException | При использовании неподдерживаемого SaveFormat, например PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### См. также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* класс [Presentation](../../presentation)
* пространство имён [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Сохраняет указанные слайды презентации в файл в указанном формате, сохраняя номера страниц.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | Путь к создаваемому файлу. |
| slides | Int32[] | Массив номеров слайдов, начиная с 1. |
| format | SaveFormat | Формат экспортируемых данных. |
| options | ISaveOptions | Дополнительные параметры формата. |

### См. также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* интерфейс [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* класс [Presentation](../../presentation)
* пространство имён [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Сохраняет указанные слайды презентации в поток в указанном формате, сохраняя номера страниц.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Выходной поток. |
| slides | Int32[] | Массив номеров слайдов, начиная с 1. |
| format | SaveFormat | Формат экспортируемых данных. |

### См. также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* класс [Presentation](../../presentation)
* пространство имён [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Сохраняет указанные слайды презентации в поток в указанном формате, сохраняя номера страниц.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Выходной поток. |
| slides | Int32[] | Массив номеров слайдов, начиная с 1. |
| format | SaveFormat | Формат экспортируемых данных. |
| options | ISaveOptions | Дополнительные параметры формата. |

### Исключения

| exception | condition |
| --- | --- |
| ArgumentNullException | Когда параметр stream или slides имеет значение null. |
| ArgumentOutOfRangeException | Когда массив slides содержит некорректные номера страниц. |
| InvalidOperationException | При использовании неподдерживаемого SaveFormat, например PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Примеры

The following example shows how to convert PowerPoint to PNG.

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

The following example shows how to convert PowerPoint to PNG with custom dimensions.

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

The following example shows how to convert PowerPoint to PNG with custom size.

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

### См. также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* интерфейс [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* класс [Presentation](../../presentation)
* пространство имён [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->