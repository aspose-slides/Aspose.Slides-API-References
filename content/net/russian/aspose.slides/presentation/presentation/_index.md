---
title: Presentation
second_title: Aspose.Sildes для .NET API Справочник
description: Этот конструктор создает новую презентацию с нуля. Созданная презентация имеет один пустой слайд.
type: docs
weight: 10
url: /ru/aspose.slides/presentation/presentation/
---

## Presentation() {#constructor}

Этот конструктор создает новую презентацию с нуля. Созданная презентация имеет один пустой слайд.

```csharp
public Presentation()
```

### См. Также

* класс [Presentation](../../presentation)
* пространство имен [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

---

## Presentation(LoadOptions) {#constructor_1}

Этот конструктор создает новую презентацию с нуля. Созданная презентация имеет один пустой слайд.

```csharp
public Presentation(LoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| loadOptions | LoadOptions | Дополнительные параметры загрузки. |

### См. Также

* класс [LoadOptions](../../loadoptions)
* класс [Presentation](../../presentation)
* пространство имен [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

---

## Presentation(Stream) {#constructor_2}

Этот конструктор является основным механизмом для чтения существующей презентации.

```csharp
public Presentation(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Входной поток. |

### Примеры

```csharp
[C#]

FileStream fis = new FileStream("demo.pptx", FileMode.Open, FileAccess.Read);
Presentation pres = new Presentation(fis);
fis.Close();

[Visual Basic]

Dim fis As FileStream = New FileStream("demo.pptx", FileMode.Open, FileAccess.Read)
Dim pres As Presentation = New Presentation(fis)
fis.Close()
```

### См. Также

* класс [Presentation](../../presentation)
* пространство имен [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

---

## Presentation(Stream, LoadOptions) {#constructor_3}

Этот конструктор является основным механизмом для чтения существующей презентации.

```csharp
public Presentation(Stream stream, LoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Входной поток. |
| loadOptions | LoadOptions | Дополнительные параметры загрузки. |

### См. Также

* класс [LoadOptions](../../loadoptions)
* класс [Presentation](../../presentation)
* пространство имен [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

---

## Presentation(string) {#constructor_4}

Этот конструктор получает путь к исходному файлу, из которого читаются содержимое презентации.

```csharp
public Presentation(string file)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| file | String | Входной файл. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда входной файл имеет нулевую длину |

### Примеры

```csharp
[C#]

Presentation pres = new Presentation("demo.pptx");

[Visual Basic]

Dim pres As Presentation = New Presentation("demo.pptx")
```

### См. Также

* класс [Presentation](../../presentation)
* пространство имен [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

---

## Presentation(string, LoadOptions) {#constructor_5}

Этот конструктор получает путь к исходному файлу, из которого читаются содержимое презентации.

```csharp
public Presentation(string file, LoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| file | String | Входной файл. |
| loadOptions | LoadOptions | Дополнительные параметры загрузки. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда входной файл имеет нулевую длину |

### См. Также

* класс [LoadOptions](../../loadoptions)
* класс [Presentation](../../presentation)
* пространство имен [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->