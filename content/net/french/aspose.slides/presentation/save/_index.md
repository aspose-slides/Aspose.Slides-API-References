---
title: Save
second_title: Référence API Aspose.Sildes pour .NET
description: Enregistre toutes les diapositives d'une présentation dans un fichier au format spécifié.
type: docs
weight: 400
url: /fr/aspose.slides/presentation/save/
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
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
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
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### Voir aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
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
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Enregistre toutes les diapositives d’une présentation dans un ensemble de fichiers représentant le balisage XAML.

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
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Enregistre les diapositives spécifiées d’une présentation dans un fichier au format spécifié en conservant le numéro de page.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| slides | Int32[] | Tableau avec les positions des diapositives, à partir de 1. |
| format | SaveFormat | Format des données exportées. |

### Exceptions

| Exception | Condition |
| --- | --- |
| ArgumentNullException | Lorsque le paramètre stream ou slides est nul. |
| ArgumentOutOfRangeException | Lorsque le paramètre slides contient des numéros de page incorrects. |
| InvalidOperationException | Lorsqu’un SaveFormat non pris en charge est utilisé, par ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Voir aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Enregistre les diapositives spécifiées d’une présentation dans un fichier au format spécifié en conservant le numéro de page.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fname | String | Chemin du fichier créé. |
| slides | Int32[] | Tableau avec les positions des diapositives, à partir de 1. |
| format | SaveFormat | Format des données exportées. |
| options | ISaveOptions | Options de format supplémentaires. |

### Voir aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Enregistre les diapositives spécifiées d’une présentation dans un flux au format spécifié en conservant le numéro de page.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Flux de sortie. |
| slides | Int32[] | Tableau avec les positions des diapositives, à partir de 1. |
| format | SaveFormat | Format des données exportées. |

### Voir aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Enregistre les diapositives spécifiées d’une présentation dans un flux au format spécifié en conservant le numéro de page.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Flux de sortie. |
| slides | Int32[] | Tableau avec les positions des diapositives, à partir de 1. |
| format | SaveFormat | Format des données exportées. |
| options | ISaveOptions | Options de format supplémentaires. |

### Exceptions

| Exception | Condition |
| --- | --- |
| ArgumentNullException | Lorsque le paramètre stream ou slides est nul. |
| ArgumentOutOfRangeException | Lorsque le paramètre slides contient des numéros de page incorrects. |
| InvalidOperationException | Lorsqu’un SaveFormat non pris en charge est utilisé, par ex. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Exemples

L’exemple suivant montre comment convertir PowerPoint en PNG.

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

L’exemple suivant montre comment convertir PowerPoint en PNG avec des dimensions personnalisées.

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

L’exemple suivant montre comment convertir PowerPoint en PNG avec une taille personnalisée.

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

### Voir aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->