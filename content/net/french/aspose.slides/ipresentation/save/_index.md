---
title: Save
second_title: Aspose.Sildes pour .NET Référence API
description: Enregistre toutes les diapositives d'une présentation dans un fichier au format spécifié.
type: docs
weight: 390
url: /fr/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

Enregistre toutes les diapositives d’une présentation dans un fichier au format spécifié.

```csharp
public void Save(string fname, SaveFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| format | SaveFormat | Format des données exportées. |

### Voir aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Flux de sortie. |
| format | SaveFormat | Format des données exportées. |

### Voir aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Enregistre toutes les diapositives d’une présentation dans un fichier au format spécifié avec des options supplémentaires.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| format | SaveFormat | Format des données exportées. |
| options | ISaveOptions | Options de format supplémentaires. |

### Voir aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié avec des options supplémentaires.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Flux de sortie. |
| format | SaveFormat | Format des données exportées. |
| options | ISaveOptions | Options de format supplémentaires. |

### Exceptions

| Exception | Condition |
| --- | --- |
| NotSupportedException | Si vous essayez d’enregistrer un fichier chiffré dans un format autre que Office 2007-2010 |

### Voir aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Enregistre les diapositives spécifiées d’une présentation dans un fichier au format spécifié.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| slides | Int32[] | Tableau contenant les positions des diapositives, à partir de 1. |
| format | SaveFormat | Format des données exportées. |

### Exceptions

| Exception | Condition |
| --- | --- |
| ArgumentNullException | Lorsque le paramètre stream ou slides est nul. |
| ArgumentOutOfRangeException | Lorsque le paramètre slides contient des numéros de page incorrects. |
| InvalidOperationException | Lorsqu’un SaveFormat non pris en charge est utilisé, par ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Voir aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Enregistre les diapositives spécifiées d’une présentation dans un fichier au format spécifié.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| slides | Int32[] | Tableau contenant les positions des diapositives, à partir de 1. |
| format | SaveFormat | Format des données exportées. |
| options | ISaveOptions | Options de format supplémentaires. |

### Exceptions

| Exception | Condition |
| --- | --- |
| ArgumentNullException | Lorsque le paramètre stream ou slides est nul. |
| ArgumentOutOfRangeException | Lorsque le paramètre slides contient des numéros de page incorrects. |
| InvalidOperationException | Lorsqu’un SaveFormat non pris en charge est utilisé, par ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Voir aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Enregistre les diapositives spécifiées d’une présentation dans un flux au format spécifié.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Flux de sortie. |
| slides | Int32[] | Tableau contenant les positions des diapositives, à partir de 1. |
| format | SaveFormat | Format des données exportées. |

### Exceptions

| Exception | Condition |
| --- | --- |
| ArgumentNullException | Lorsque le paramètre stream ou slides est nul. |
| ArgumentOutOfRangeException | Lorsque le paramètre slides contient des numéros de page incorrects. |
| InvalidOperationException | Lorsqu’un SaveFormat non pris en charge est utilisé, par ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Voir aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Enregistre les diapositives spécifiées d’une présentation dans un flux au format spécifié.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Flux de sortie. |
| slides | Int32[] | Tableau contenant les positions des diapositives, à partir de 1. |
| format | SaveFormat | Format des données exportées. |
| options | ISaveOptions | Options de format supplémentaires. |

### Exceptions

| Exception | Condition |
| --- | --- |
| ArgumentNullException | Lorsque le paramètre stream ou slides est nul. |
| ArgumentOutOfRangeException | Lorsque le paramètre slides contient des numéros de page incorrects. |
| InvalidOperationException | Lorsqu’un SaveFormat non pris en charge est utilisé, par ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Voir aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Enregistre toutes les diapositives d’une présentation sous forme d’ensemble de fichiers représentant le balisage XAML.

```csharp
public void Save(IXamlOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | IXamlOptions | Les options du format XAML. |

### Exemples

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Voir aussi

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->