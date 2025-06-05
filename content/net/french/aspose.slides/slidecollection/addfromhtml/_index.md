---
title: AddFromHtml
second_title: Aspose.Sildes pour la référence API .NET
description: Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection.
type: docs
weight: 70
url: /fr/aspose.slides/slidecollection/addfromhtml/
---

## AddFromHtml(string, IExternalResourceResolver, string) {#addfromhtml_5}

Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection.

```csharp
public ISlide[] AddFromHtml(string htmlText, IExternalResourceResolver resolver, string uri)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlText | String | Html à ajouter. |
| resolver | IExternalResourceResolver | Un objet de rappel utilisé pour récupérer des objets externes. Si ce paramètre est nul, tous les objets externes seront ignorés. |
| uri | String | Un URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |

### Valeur de retour

Diapositives ajoutées.

### Voir aussi

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(string) {#addfromhtml_4}

Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection.

```csharp
public ISlide[] AddFromHtml(string htmlText)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlText | String | Html à ajouter. |

### Valeur de retour

Diapositives ajoutées

### Voir aussi

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader, IExternalResourceResolver, string) {#addfromhtml_3}

Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader, IExternalResourceResolver resolver, string uri)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlReader | TextReader | Objet TextReader qui sera utilisé comme source d'un fichier HTML. |
| resolver | IExternalResourceResolver | Un objet de rappel utilisé pour récupérer des objets externes. Si ce paramètre est nul, tous les objets externes seront ignorés. |
| uri | String | Un URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |

### Valeur de retour

Diapositives ajoutées.

### Voir aussi

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader) {#addfromhtml_2}

Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlReader | TextReader | Objet TextReader qui sera utilisé comme source d'un fichier HTML. |

### Valeur de retour

Diapositives ajoutées

### Voir aussi

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(Stream, IExternalResourceResolver, string) {#addfromhtml_1}

Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream, IExternalResourceResolver resolver, string uri)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlStream | Stream | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |
| resolver | IExternalResourceResolver | Un objet de rappel utilisé pour récupérer des objets externes. Si ce paramètre est nul, tous les objets externes seront ignorés. |
| uri | String | Un URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |

### Valeur de retour

Diapositives ajoutées.

### Voir aussi

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(Stream) {#addfromhtml}

Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlStream | Stream | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |

### Valeur de retour

Diapositives ajoutées

### Exemples

```csharp
[C#]
// Créer une instance de la classe Presentation.
using (var presentation = new Presentation())
{
    using (var htmlStream = File.OpenRead("page.html"))
    {
        // Appeler la méthode AddFromHtml et passer le fichier HTML.
        presentation.Slides.AddFromHtml(htmlStream);
    }
    // Utiliser la méthode Save pour enregistrer le fichier en tant que document PowerPoint.
    presentation.Save("MyPresentation.pptx", SaveFormat.Pptx);
}
```

### Voir aussi

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->