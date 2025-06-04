---
title: Save
second_title: Aspose.Sildes pour .NET Référence API
description: Enregistre toutes les diapositives d'une présentation dans un fichier avec le format spécifié.
type: docs
weight: 370
url: /fr/aspose.slides/ipresentation/save/
---

## Save(string, SaveFormat) {#save_5}

Enregistre toutes les diapositives d'une présentation dans un fichier avec le format spécifié.

```csharp
public void Save(string fname, SaveFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fname | String | Chemin vers le fichier créé. |
| format | SaveFormat | Format des données exportées. |

### Voir également

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Enregistre toutes les diapositives d'une présentation dans un flux dans le format spécifié.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Flux de sortie. |
| format | SaveFormat | Format des données exportées. |

### Voir également

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Enregistre toutes les diapositives d'une présentation dans un fichier avec le format spécifié et des options supplémentaires.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fname | String | Chemin vers le fichier créé. |
| format | SaveFormat | Format des données exportées. |
| options | ISaveOptions | Options de format supplémentaires. |

### Voir également

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Enregistre toutes les diapositives d'une présentation dans un flux dans le format spécifié et avec des options supplémentaires.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Flux de sortie. |
| format | SaveFormat | Format des données exportées. |
| options | ISaveOptions | Options de format supplémentaires. |

### Exceptions

| exception | condition |
| --- | --- |
| NotSupportedException | Si vous essayez d'enregistrer un fichier crypté dans un format qui n'est pas Office 2007-2010 |

### Voir également

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Enregistre les diapositives spécifiées d'une présentation dans un fichier avec le format spécifié.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fname | String | Chemin vers le fichier créé. |
| slides | Int32[] | Tableau avec les positions des diapositives, en commençant par 1. |
| format | SaveFormat | Format des données exportées. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lorsque le flux ou le paramètre slides est nul. |
| ArgumentOutOfRangeException | Lorsque le paramètre slides contient de mauvais numéros de page. |
| InvalidOperationException | Lorsque SaveFormat non pris en charge est utilisé, par exemple PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Voir également

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Enregistre les diapositives spécifiées d'une présentation dans un fichier avec le format spécifié.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fname | String | Chemin vers le fichier créé. |
| slides | Int32[] | Tableau avec les positions des diapositives, en commençant par 1. |
| format | SaveFormat | Format des données exportées. |
| options | ISaveOptions | Options de format supplémentaires. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lorsque le flux ou le paramètre slides est nul. |
| ArgumentOutOfRangeException | Lorsque le paramètre slides contient de mauvais numéros de page. |
| InvalidOperationException | Lorsque SaveFormat non pris en charge est utilisé, par exemple PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Voir également

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Enregistre les diapositives spécifiées d'une présentation dans un flux dans le format spécifié.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Flux de sortie. |
| slides | Int32[] | Tableau avec les positions des diapositives, en commençant par 1. |
| format | SaveFormat | Format des données exportées. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lorsque le flux ou le paramètre slides est nul. |
| ArgumentOutOfRangeException | Lorsque le paramètre slides contient de mauvais numéros de page. |
| InvalidOperationException | Lorsque SaveFormat non pris en charge est utilisé, par exemple PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Voir également

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Enregistre les diapositives spécifiées d'une présentation dans un flux dans le format spécifié.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Flux de sortie. |
| slides | Int32[] | Tableau avec les positions des diapositives, en commençant par 1. |
| format | SaveFormat | Format des données exportées. |
| options | ISaveOptions | Options de format supplémentaires. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lorsque le flux ou le paramètre slides est nul. |
| ArgumentOutOfRangeException | Lorsque le paramètre slides contient de mauvais numéros de page. |
| InvalidOperationException | Lorsque SaveFormat non pris en charge est utilisé, par exemple PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Voir également

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Enregistre toutes les diapositives d'une présentation dans un ensemble de fichiers représentant un balisage XAML.

```csharp
public void Save(IXamlOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | IXamlOptions | Options de format XAML. |

### Exemples

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Voir également

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->