---
title: Enregistrer
second_title: Référence de l'API Aspose.Slides pour .NET
description: Enregistre toutes les diapositives d'une présentation dans un fichier avec le format spécifié.
type: docs
weight: 370
url: /fr/aspose.slides/ipresentation/save/
---

## Enregistrer(string, SaveFormat) {#save_5}

Enregistre toutes les diapositives d'une présentation dans un fichier avec le format spécifié.

```csharp
public void Save(string fname, SaveFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fname | String | Chemin vers le fichier créé. |
| format | SaveFormat | Format des données exportées. |

### Voir aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Enregistrer(Stream, SaveFormat) {#save_1}

Enregistre toutes les diapositives d'une présentation dans un flux dans le format spécifié.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Flux de sortie. |
| format | SaveFormat | Format des données exportées. |

### Voir aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Enregistrer(string, SaveFormat, ISaveOptions) {#save_6}

Enregistre toutes les diapositives d'une présentation dans un fichier avec le format spécifié et avec des options supplémentaires.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fname | String | Chemin vers le fichier créé. |
| format | SaveFormat | Format des données exportées. |
| options | ISaveOptions | Options de format supplémentaires. |

### Voir aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Enregistrer(Stream, SaveFormat, ISaveOptions) {#save_2}

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
| NotSupportedException | Si vous essayez d'enregistrer un fichier chiffré dans un format autre que Office 2007-2010 |

### Voir aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Enregistrer(string, int[], SaveFormat) {#save_7}

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
| ArgumentNullException | Lorsque le flux ou le paramètre des diapositives est nul. |
| ArgumentOutOfRangeException | Lorsque le paramètre des diapositives contient de mauvais numéros de page. |
| InvalidOperationException | Lorsque un SaveFormat non pris en charge est utilisé, par exemple PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Voir aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Enregistrer(string, int[], SaveFormat, ISaveOptions) {#save_8}

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
| ArgumentNullException | Lorsque le flux ou le paramètre des diapositives est nul. |
| ArgumentOutOfRangeException | Lorsque le paramètre des diapositives contient de mauvais numéros de page. |
| InvalidOperationException | Lorsque un SaveFormat non pris en charge est utilisé, par exemple PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Voir aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Enregistrer(Stream, int[], SaveFormat) {#save_3}

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
| ArgumentNullException | Lorsque le flux ou le paramètre des diapositives est nul. |
| ArgumentOutOfRangeException | Lorsque le paramètre des diapositives contient de mauvais numéros de page. |
| InvalidOperationException | Lorsque un SaveFormat non pris en charge est utilisé, par exemple PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Voir aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Enregistrer(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

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
| ArgumentNullException | Lorsque le flux ou le paramètre des diapositives est nul. |
| ArgumentOutOfRangeException | Lorsque le paramètre des diapositives contient de mauvais numéros de page. |
| InvalidOperationException | Lorsque un SaveFormat non pris en charge est utilisé, par exemple PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Voir aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Enregistrer(IXamlOptions) {#save}

Enregistre toutes les diapositives d'une présentation dans un ensemble de fichiers représentant le balisage XAML.

```csharp
public void Save(IXamlOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | IXamlOptions | Les options de format XAML. |

### Exemples

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Voir aussi

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->