---
title: Save
second_title: Référence de l'API Aspose.Slides pour .NET
description: Sauvegarde les diapositives spécifiées d'une présentation dans un fichier avec le format spécifié en conservant le numéro de page.
type: docs
weight: 380
url: /fr/aspose.slides/presentation/save/
---

## Save(string, int[], SaveFormat) {#save_7}

Sauvegarde les diapositives spécifiées d'une présentation dans un fichier avec le format spécifié en conservant le numéro de page.

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
| ArgumentNullException | Lorsque le paramètre stream ou slides est null. |
| ArgumentOutOfRangeException | Lorsque le paramètre slides contient des numéros de page incorrects. |
| InvalidOperationException | Lorsque un SaveFormat non pris en charge est utilisé, par exemple PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Voir Aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Sauvegarde les diapositives spécifiées d'une présentation dans un fichier avec le format spécifié en conservant le numéro de page.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fname | String | Chemin vers le fichier créé. |
| slides | Int32[] | Tableau avec les positions des diapositives, en commençant par 1. |
| format | SaveFormat | Format des données exportées. |
| options | ISaveOptions | Options de format supplémentaires. |

### Voir Aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Sauvegarde les diapositives spécifiées d'une présentation dans un flux dans le format spécifié en conservant le numéro de page.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Flux de sortie. |
| slides | Int32[] | Tableau avec les positions des diapositives, en commençant par 1. |
| format | SaveFormat | Format des données exportées. |

### Voir Aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Sauvegarde les diapositives spécifiées d'une présentation dans un flux dans le format spécifié en conservant le numéro de page.

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
| ArgumentNullException | Lorsque le paramètre stream ou slides est null. |
| ArgumentOutOfRangeException | Lorsque le paramètre slides contient des numéros de page incorrects. |
| InvalidOperationException | Lorsque un SaveFormat non pris en charge est utilisé, par exemple PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Exemples

L'exemple suivant montre comment convertir PowerPoint en PNG.

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

L'exemple suivant montre comment convertir PowerPoint en PNG avec des dimensions personnalisées.

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

L'exemple suivant montre comment convertir PowerPoint en PNG avec une taille personnalisée.

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

### Voir Aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat) {#save_5}

Sauvegarde toutes les diapositives d'une présentation dans un fichier avec le format spécifié.

```csharp
public void Save(string fname, SaveFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fname | String | Chemin vers le fichier créé. |
| format | SaveFormat | Format des données exportées. |

### Voir Aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Sauvegarde toutes les diapositives d'une présentation dans un flux dans le format spécifié.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Flux de sortie. |
| format | SaveFormat | Format des données exportées. |

### Voir Aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### Voir Aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Sauvegarde toutes les diapositives d'une présentation dans un flux dans le format spécifié et avec des options supplémentaires.

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
| NotSupportedException | Si vous essayez de sauvegarder un fichier crypté dans un format non Office 2007-2010 |

### Voir Aussi

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Sauvegarde toutes les diapositives d'une présentation dans un ensemble de fichiers représentant du balisage XAML.

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

### Voir Aussi

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->