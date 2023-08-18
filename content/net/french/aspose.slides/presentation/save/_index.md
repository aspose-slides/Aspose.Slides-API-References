---
title: Save
second_title: Référence de l'API Aspose.Slides pour .NET
description: Enregistre les diapositives spécifiées dune présentation dans un fichier au format spécifié en conservant le numéro de page.
type: docs
weight: 350
url: /fr/aspose.slides/presentation/save/
---
## Save(string, int[], SaveFormat) {#save_9}

Enregistre les diapositives spécifiées d'une présentation dans un fichier au format spécifié en conservant le numéro de page.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fname | String | Chemin d'accès au fichier créé. |
| slides | Int32[] | Tableau avec positions de diapositives, à partir de 1. |
| format | SaveFormat | Format des données exportées. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lorsque le paramètre de flux ou de diapositives est nul. |
| ArgumentOutOfRangeException | Lorsque le paramètre des diapositives contient des numéros de page erronés. |
| InvalidOperationException | Lorsqu'un SaveFormat non pris en charge est utilisé, par exemple PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Voir également

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* espace de noms [Aspose.Slides](../../presentation)
* Assemblée [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_10}

Enregistre les diapositives spécifiées d'une présentation dans un fichier au format spécifié en conservant le numéro de page.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fname | String | Chemin d'accès au fichier créé. |
| slides | Int32[] | Tableau avec positions de diapositives, à partir de 1. |
| format | SaveFormat | Format des données exportées. |
| options | ISaveOptions | Options de formats supplémentaires. |

### Voir également

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* espace de noms [Aspose.Slides](../../presentation)
* Assemblée [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié en conservant le numéro de page.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Flux de sortie. |
| slides | Int32[] | Tableau avec positions de diapositives, à partir de 1. |
| format | SaveFormat | Format des données exportées. |

### Voir également

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* espace de noms [Aspose.Slides](../../presentation)
* Assemblée [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié en conservant le numéro de page.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Flux de sortie. |
| slides | Int32[] | Tableau avec positions de diapositives, à partir de 1. |
| format | SaveFormat | Format des données exportées. |
| options | ISaveOptions | Options de formats supplémentaires. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lorsque le paramètre de flux ou de diapositives est nul. |
| ArgumentOutOfRangeException | Lorsque le paramètre des diapositives contient des numéros de page erronés. |
| InvalidOperationException | Lorsqu'un SaveFormat non pris en charge est utilisé, par exemple PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Voir également

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* espace de noms [Aspose.Slides](../../presentation)
* Assemblée [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, HttpResponse, bool) {#save_8}

Envoie la présentation au navigateur client. Cette méthode est absente des versions ClientProfile d'Aspose.Slide.

```csharp
public void Save(string fname, SaveFormat format, HttpResponse response, bool showInline)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fname | String | Le nom de la présentation qui apparaîtra sur le navigateur client. Le nom ne doit pas contenir de chemin. |
| format | SaveFormat | Format des données exportées. |
| response | HttpResponse | Objet de réponse où enregistrer le document. |
| showInline | Boolean | True pour afficher une option permettant d'ouvrir la présentation dans le navigateur. |

### Voir également

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* espace de noms [Aspose.Slides](../../presentation)
* Assemblée [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions, HttpResponse, bool) {#save_7}

Envoie la présentation au navigateur client. Cette méthode est absente des versions ClientProfile d'Aspose.Slide.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options, HttpResponse response, 
    bool showInline)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fname | String | Le nom de la présentation qui apparaîtra sur le navigateur client. Le nom ne doit pas contenir de chemin. |
| format | SaveFormat | Format des données exportées. |
| options | ISaveOptions | Options de formats supplémentaires. |
| response | HttpResponse | Objet de réponse où enregistrer le document. |
| showInline | Boolean | True pour afficher une option permettant d'ouvrir la présentation dans le navigateur. |

### Voir également

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* espace de noms [Aspose.Slides](../../presentation)
* Assemblée [Aspose.Slides](../../../)

---

## Save(string, SaveFormat) {#save_5}

Enregistre toutes les diapositives d'une présentation dans un fichier au format spécifié.

```csharp
public void Save(string fname, SaveFormat format)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fname | String | Chemin d'accès au fichier créé. |
| format | SaveFormat | Format des données exportées. |

### Voir également

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* espace de noms [Aspose.Slides](../../presentation)
* Assemblée [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Flux de sortie. |
| format | SaveFormat | Format des données exportées. |

### Voir également

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* espace de noms [Aspose.Slides](../../presentation)
* Assemblée [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Enregistre toutes les diapositives d'une présentation dans un fichier au format spécifié et avec des options supplémentaires.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fname | String | Chemin d'accès au fichier créé. |
| format | SaveFormat | Format des données exportées. |
| options | ISaveOptions | Options de formats supplémentaires. |

### Voir également

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* espace de noms [Aspose.Slides](../../presentation)
* Assemblée [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié et avec des options supplémentaires.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Flux de sortie. |
| format | SaveFormat | Format des données exportées. |
| options | ISaveOptions | Options de formats supplémentaires. |

### Exceptions

| exception | condition |
| --- | --- |
| NotSupportedException | Si vous essayez d'enregistrer un fichier crypté au format none Office 2007-2010 |

### Voir également

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* espace de noms [Aspose.Slides](../../presentation)
* Assemblée [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Enregistre toutes les diapositives d'une présentation dans un ensemble de fichiers représentant le balisage XAML.

```csharp
public void Save(IXamlOptions options)
```

| Paramètre | Taper | La description |
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

### Voir également

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* class [Presentation](../../presentation)
* espace de noms [Aspose.Slides](../../presentation)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
