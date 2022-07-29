---
title: Save
second_title: Referencia de la API de Aspose.Slides para .NET
description: Guarda las diapositivas especificadas de una presentación en un archivo con el formato especificado manteniendo el número de página.
type: docs
weight: 340
url: /es/net/aspose.slides/presentation/save/
---
## Save(string, int[], SaveFormat) {#save_7}

Guarda las diapositivas especificadas de una presentación en un archivo con el formato especificado manteniendo el número de página.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fname | String | Ruta al archivo creado. |
| slides | Int32[] | Matriz con posiciones de diapositivas, a partir de 1. |
| format | SaveFormat | Formato de los datos exportados. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Cuando el parámetro de transmisión o diapositivas es nulo. |
| ArgumentOutOfRangeException | Cuando el parámetro de diapositivas contiene números de página incorrectos. |
| InvalidOperationException | Cuando se utiliza un SaveFormat no compatible, por ejemplo, PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Ver también

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* espacio de nombres [Aspose.Slides](../../presentation)
* asamblea [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Guarda las diapositivas especificadas de una presentación en un archivo con el formato especificado manteniendo el número de página.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fname | String | Ruta al archivo creado. |
| slides | Int32[] | Matriz con posiciones de diapositivas, a partir de 1. |
| format | SaveFormat | Formato de los datos exportados. |
| options | ISaveOptions | Opciones de formato adicionales. |

### Ver también

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* espacio de nombres [Aspose.Slides](../../presentation)
* asamblea [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Guarda las diapositivas especificadas de una presentación en una secuencia en el formato especificado manteniendo el número de página.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | Salida de corriente. |
| slides | Int32[] | Matriz con posiciones de diapositivas, a partir de 1. |
| format | SaveFormat | Formato de los datos exportados. |

### Ver también

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* espacio de nombres [Aspose.Slides](../../presentation)
* asamblea [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Guarda las diapositivas especificadas de una presentación en una secuencia en el formato especificado manteniendo el número de página.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | Salida de corriente. |
| slides | Int32[] | Matriz con posiciones de diapositivas, a partir de 1. |
| format | SaveFormat | Formato de los datos exportados. |
| options | ISaveOptions | Opciones de formato adicionales. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Cuando el parámetro de transmisión o diapositivas es nulo. |
| ArgumentOutOfRangeException | Cuando el parámetro de diapositivas contiene números de página incorrectos. |
| InvalidOperationException | Cuando se utiliza un SaveFormat no compatible, por ejemplo, PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Ver también

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* espacio de nombres [Aspose.Slides](../../presentation)
* asamblea [Aspose.Slides](../../../)

---

## Save(string, SaveFormat) {#save_5}

Guarda todas las diapositivas de una presentación en un archivo con el formato especificado.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fname | String | Ruta al archivo creado. |
| format | SaveFormat | Formato de los datos exportados. |

### Ver también

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* espacio de nombres [Aspose.Slides](../../presentation)
* asamblea [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Guarda todas las diapositivas de una presentación en una transmisión en el formato especificado.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | Salida de corriente. |
| format | SaveFormat | Formato de los datos exportados. |

### Ver también

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* espacio de nombres [Aspose.Slides](../../presentation)
* asamblea [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Guarda todas las diapositivas de una presentación en un archivo con el formato especificado y con opciones adicionales.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fname | String | Ruta al archivo creado. |
| format | SaveFormat | Formato de los datos exportados. |
| options | ISaveOptions | Opciones de formato adicionales. |

### Ver también

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* espacio de nombres [Aspose.Slides](../../presentation)
* asamblea [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Guarda todas las diapositivas de una presentación en una secuencia en el formato especificado y con opciones adicionales.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | Salida de corriente. |
| format | SaveFormat | Formato de los datos exportados. |
| options | ISaveOptions | Opciones de formato adicionales. |

### Excepciones

| excepción | condición |
| --- | --- |
| NotSupportedException | Si intenta guardar un archivo cifrado en formato ninguno de Office 2007-2010 |

### Ver también

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* espacio de nombres [Aspose.Slides](../../presentation)
* asamblea [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Guarda todas las diapositivas de una presentación en un conjunto de archivos que representan el marcado XAML.

```csharp
public void Save(IXamlOptions options)
```

| Parámetro | Escribe | Descripción |
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

### Ver también

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* class [Presentation](../../presentation)
* espacio de nombres [Aspose.Slides](../../presentation)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
