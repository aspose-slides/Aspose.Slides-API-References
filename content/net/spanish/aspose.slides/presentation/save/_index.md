---
title: Guardar
second_title: Referencia de la API de Aspose.Slides para .NET
description: Guarda diapositivas específicas de una presentación en un archivo con el formato especificado manteniendo el número de página.
type: docs
weight: 380
url: /es/aspose.slides/presentation/save/
---

## Save(string, int[], SaveFormat) {#save_7}

Guarda diapositivas específicas de una presentación en un archivo con el formato especificado manteniendo el número de página.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fname | String | Ruta al archivo creado. |
| slides | Int32[] | Matriz con las posiciones de las diapositivas, comenzando desde 1. |
| format | SaveFormat | Formato de los datos exportados. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Cuando el parámetro de stream o slides es nulo. |
| ArgumentOutOfRangeException | Cuando el parámetro de slides contiene números de página incorrectos. |
| InvalidOperationException | Cuando se utiliza un SaveFormat no admitido, por ejemplo, PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Ver También

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Guarda diapositivas específicas de una presentación en un archivo con el formato especificado manteniendo el número de página.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fname | String | Ruta al archivo creado. |
| slides | Int32[] | Matriz con las posiciones de las diapositivas, comenzando desde 1. |
| format | SaveFormat | Formato de los datos exportados. |
| options | ISaveOptions | Opciones adicionales de formato. |

### Ver También

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Guarda diapositivas específicas de una presentación en un stream en el formato especificado manteniendo el número de página.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Stream de salida. |
| slides | Int32[] | Matriz con las posiciones de las diapositivas, comenzando desde 1. |
| format | SaveFormat | Formato de los datos exportados. |

### Ver También

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Guarda diapositivas específicas de una presentación en un stream en el formato especificado manteniendo el número de página.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Stream de salida. |
| slides | Int32[] | Matriz con las posiciones de las diapositivas, comenzando desde 1. |
| format | SaveFormat | Formato de los datos exportados. |
| options | ISaveOptions | Opciones adicionales de formato. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Cuando el parámetro de stream o slides es nulo. |
| ArgumentOutOfRangeException | Cuando el parámetro de slides contiene números de página incorrectos. |
| InvalidOperationException | Cuando se utiliza un SaveFormat no admitido, por ejemplo, PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Ejemplos

El siguiente ejemplo muestra cómo convertir PowerPoint a PNG.

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

El siguiente ejemplo muestra cómo convertir PowerPoint a PNG con dimensiones personalizadas.

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

El siguiente ejemplo muestra cómo convertir PowerPoint a PNG con un tamaño personalizado.

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

### Ver También

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat) {#save_5}

Guarda todas las diapositivas de una presentación en un archivo con el formato especificado.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fname | String | Ruta al archivo creado. |
| format | SaveFormat | Formato de los datos exportados. |

### Ver También

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Guarda todas las diapositivas de una presentación en un stream en el formato especificado.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Stream de salida. |
| format | SaveFormat | Formato de los datos exportados. |

### Ver También

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### Ver También

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Guarda todas las diapositivas de una presentación en un stream en el formato especificado y con opciones adicionales.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Stream de salida. |
| format | SaveFormat | Formato de los datos exportados. |
| options | ISaveOptions | Opciones adicionales de formato. |

### Excepciones

| excepción | condición |
| --- | --- |
| NotSupportedException | Si intentas guardar un archivo encriptado en un formato que no es de Office 2007-2010 |

### Ver También

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Guarda todas las diapositivas de una presentación en un conjunto de archivos que representan el marcado XAML.

```csharp
public void Save(IXamlOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | IXamlOptions | Las opciones del formato XAML. |

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Ver También

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->