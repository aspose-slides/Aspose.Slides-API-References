---
title: Save
second_title: Aspose.Slides para .NET API Reference
description: Guarda todas las diapositivas de una presentación en un archivo con el formato especificado.
type: docs
weight: 370
url: /es/aspose.slides/ipresentation/save/
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
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Guarda todas las diapositivas de una presentación en un flujo en el formato especificado.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Flujo de salida. |
| format | SaveFormat | Formato de los datos exportados. |

### Ver También

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Guarda todas las diapositivas de una presentación en un archivo con el formato especificado y con opciones adicionales.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fname | String | Ruta al archivo creado. |
| format | SaveFormat | Formato de los datos exportados. |
| options | ISaveOptions | Opciones adicionales de formato. |

### Ver También

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Guarda todas las diapositivas de una presentación en un flujo en el formato especificado y con opciones adicionales.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Flujo de salida. |
| format | SaveFormat | Formato de los datos exportados. |
| options | ISaveOptions | Opciones adicionales de formato. |

### Excepciones

| excepción | condición |
| --- | --- |
| NotSupportedException | Si intentas guardar un archivo cifrado en un formato que no es Office 2007-2010 |

### Ver También

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Guarda las diapositivas especificadas de una presentación en un archivo con el formato especificado.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fname | String | Ruta al archivo creado. |
| slides | Int32[] | Array con las posiciones de las diapositivas, comenzando desde 1. |
| format | SaveFormat | Formato de los datos exportados. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Cuando el flujo o el parámetro de diapositivas es nulo. |
| ArgumentOutOfRangeException | Cuando el parámetro de diapositivas contiene números de página incorrectos. |
| InvalidOperationException | Cuando se utiliza un SaveFormat no admitido, por ejemplo, PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Ver También

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Guarda las diapositivas especificadas de una presentación en un archivo con el formato especificado.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fname | String | Ruta al archivo creado. |
| slides | Int32[] | Array con las posiciones de las diapositivas, comenzando desde 1. |
| format | SaveFormat | Formato de los datos exportados. |
| options | ISaveOptions | Opciones adicionales de formato. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Cuando el flujo o el parámetro de diapositivas es nulo. |
| ArgumentOutOfRangeException | Cuando el parámetro de diapositivas contiene números de página incorrectos. |
| InvalidOperationException | Cuando se utiliza un SaveFormat no admitido, por ejemplo, PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Ver También

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Guarda las diapositivas especificadas de una presentación en un flujo en el formato especificado.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Flujo de salida. |
| slides | Int32[] | Array con las posiciones de las diapositivas, comenzando desde 1. |
| format | SaveFormat | Formato de los datos exportados. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Cuando el flujo o el parámetro de diapositivas es nulo. |
| ArgumentOutOfRangeException | Cuando el parámetro de diapositivas contiene números de página incorrectos. |
| InvalidOperationException | Cuando se utiliza un SaveFormat no admitido, por ejemplo, PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Ver También

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Guarda las diapositivas especificadas de una presentación en un flujo en el formato especificado.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Flujo de salida. |
| slides | Int32[] | Array con las posiciones de las diapositivas, comenzando desde 1. |
| format | SaveFormat | Formato de los datos exportados. |
| options | ISaveOptions | Opciones adicionales de formato. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Cuando el flujo o el parámetro de diapositivas es nulo. |
| ArgumentOutOfRangeException | Cuando el parámetro de diapositivas contiene números de página incorrectos. |
| InvalidOperationException | Cuando se utiliza un SaveFormat no admitido, por ejemplo, PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Ver También

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Guarda todas las diapositivas de una presentación en un conjunto de archivos que representan la marca XAML.

```csharp
public void Save(IXamlOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | IXamlOptions | Las opciones de formato XAML. |

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
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->