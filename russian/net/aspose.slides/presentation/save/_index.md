---
title: Save
second_title: Справочник по API Aspose.Slides для .NET
description: Сохраняет указанные слайды презентации в файл заданного формата с сохранением номера страницы.
type: docs
weight: 340
url: /ru/net/aspose.slides/presentation/save/
---
## Save(string, int[], SaveFormat) {#save_7}

Сохраняет указанные слайды презентации в файл заданного формата с сохранением номера страницы.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fname | String | Путь к созданному файлу. |
| slides | Int32[] | Массив позиций слайдов, начиная с 1. |
| format | SaveFormat | Формат экспортируемых данных . |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Когда параметр потока или слайдов имеет значение null. |
| ArgumentOutOfRangeException | Когда параметр слайдов содержит неверные номера страниц. |
| InvalidOperationException | Когда используется неподдерживаемый формат сохранения, например, PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Смотрите также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* пространство имен [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Сохраняет указанные слайды презентации в файл заданного формата с сохранением номера страницы.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fname | String | Путь к созданному файлу. |
| slides | Int32[] | Массив позиций слайдов, начиная с 1. |
| format | SaveFormat | Формат экспортируемых данных . |
| options | ISaveOptions | Дополнительные параметры формата. |

### Смотрите также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* пространство имен [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Сохраняет указанные слайды презентации в поток в указанном формате с сохранением номера страницы.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Выходной поток. |
| slides | Int32[] | Массив позиций слайдов, начиная с 1. |
| format | SaveFormat | Формат экспортируемых данных . |

### Смотрите также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* пространство имен [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Сохраняет указанные слайды презентации в поток в указанном формате с сохранением номера страницы.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Выходной поток. |
| slides | Int32[] | Массив позиций слайдов, начиная с 1. |
| format | SaveFormat | Формат экспортируемых данных . |
| options | ISaveOptions | Дополнительные параметры формата. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Когда параметр потока или слайдов имеет значение null. |
| ArgumentOutOfRangeException | Когда параметр слайдов содержит неверные номера страниц. |
| InvalidOperationException | Когда используется неподдерживаемый формат сохранения, например, PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Смотрите также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* пространство имен [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

---

## Save(string, SaveFormat) {#save_5}

Сохраняет все слайды презентации в файл указанного формата.

```csharp
public void Save(string fname, SaveFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fname | String | Путь к созданному файлу. |
| format | SaveFormat | Формат экспортируемых данных. |

### Смотрите также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* пространство имен [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

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

### Смотрите также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* пространство имен [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Сохраняет все слайды презентации в файл заданного формата и с дополнительными параметрами.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fname | String | Путь к созданному файлу. |
| format | SaveFormat | Формат экспортируемых данных. |
| options | ISaveOptions | Дополнительные параметры формата. |

### Смотрите также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* пространство имен [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

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
| NotSupportedException | Если вы попытаетесь сохранить зашифрованный файл в формате none Office 2007-2010 |

### Смотрите также

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* пространство имен [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Сохраняет все слайды презентации в набор файлов, представляющих разметку XAML.

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

### Смотрите также

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* class [Presentation](../../presentation)
* пространство имен [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
