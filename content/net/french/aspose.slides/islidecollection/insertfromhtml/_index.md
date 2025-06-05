---
title: InsertFromHtml
second_title: Aspose.Sildes pour .NET Référence API
description: Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée.
type: docs
weight: 90
url: /fr/aspose.slides/islidecollection/insertfromhtml/
---

## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Position à insérer. |
| htmlText | String | HTML à ajouter. |
| resolver | IExternalResourceResolver | Un objet de rappel utilisé pour récupérer des objets externes. Si ce paramètre est nul, tous les objets externes seront ignorés. |
| uri | String | Un URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |

### Return Value

Diapositives ajoutées.

### See Also

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Position à insérer. |
| htmlText | String | HTML à ajouter. |

### Return Value

Diapositives ajoutées.

### See Also

* interface [ISlide](../../islide)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Position à insérer. |
| htmlReader | TextReader | Objet TextReader qui sera utilisé comme source d'un fichier HTML. |
| resolver | IExternalResourceResolver | Un objet de rappel utilisé pour récupérer des objets externes. Si ce paramètre est nul, tous les objets externes seront ignorés. |
| uri | String | Un URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |

### Return Value

Diapositives ajoutées.

### See Also

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Position à insérer. |
| htmlReader | TextReader | Objet TextReader qui sera utilisé comme source d'un fichier HTML. |

### Return Value

Diapositives ajoutées.

### See Also

* interface [ISlide](../../islide)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Position à insérer. |
| htmlStream | Stream | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |
| resolver | IExternalResourceResolver | Un objet de rappel utilisé pour récupérer des objets externes. Si ce paramètre est nul, tous les objets externes seront ignorés. |
| uri | String | Un URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |

### Return Value

Diapositives ajoutées.

### See Also

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Position à insérer. |
| htmlStream | Stream | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |

### Return Value

Diapositives ajoutées.

### See Also

* interface [ISlide](../../islide)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Position à insérer. |
| htmlText | String | HTML à ajouter. |
| useSlideWithIndexAsStart | Boolean | Ce drapeau détermine comment commencer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index spécifié. Si **true**, l'insertion des données commencera à partir d'un espace vide sur la diapositive avec l'index spécifié. Si **false**, les données seront ajoutées aux diapositives créées. |

### Return Value

Diapositives ajoutées.

### See Also

* interface [ISlide](../../islide)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Position à insérer. |
| htmlText | String | HTML à ajouter. |
| resolver | IExternalResourceResolver | Un objet de rappel utilisé pour récupérer des objets externes. Si ce paramètre est nul, tous les objets externes seront ignorés. |
| uri | String | Un URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |
| useSlideWithIndexAsStart | Boolean | Ce drapeau détermine comment commencer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index spécifié. Si **true**, l'insertion des données commencera à partir d'un espace vide sur la diapositive avec l'index spécifié. Si **false**, les données seront ajoutées aux diapositives créées. |

### Return Value

Diapositives ajoutées.

### See Also

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Position à insérer. |
| htmlStream | Stream | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |
| useSlideWithIndexAsStart | Boolean | Ce drapeau détermine comment commencer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index spécifié. Si **true**, l'insertion des données commencera à partir d'un espace vide sur la diapositive avec l'index spécifié. Si **false**, les données seront ajoutées aux diapositives créées. |

### Return Value

Diapositives ajoutées.

### See Also

* interface [ISlide](../../islide)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Position à insérer. |
| htmlStream | Stream | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |
| resolver | IExternalResourceResolver | Un objet de rappel utilisé pour récupérer des objets externes. Si ce paramètre est nul, tous les objets externes seront ignorés. |
| uri | String | Un URI du HTML spécifié. Utilisé pour résoudre les liens relatifs. |
| useSlideWithIndexAsStart | Boolean | Ce drapeau détermine comment commencer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index spécifié. Si **true**, l'insertion des données commencera à partir d'un espace vide sur la diapositive avec l'index spécifié. Si **false**, les données seront ajoutées aux diapositives créées. |

### Return Value

Diapositives ajoutées.

### See Also

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->