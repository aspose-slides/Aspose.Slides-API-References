---
title: InsertFromHtml()
second_title: Référence API Aspose.Slides pour C++
description: Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.
type: docs
weight: 209
url: /fr/aspose.slides/slidecollection/insertfromhtml/
---
## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) méthode


Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position d'insertion. |
| htmlText | [System::String](../../../system/string/) | HTML à ajouter. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | [System::String](../../../system/string/) | Une URI du HTML spécifié. Utilisée pour résoudre les liens relatifs. |

### Valeur de retour

Diapositives ajoutées.

## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) méthode


Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position d'insertion. |
| htmlText | [System::String](../../../system/string/) | HTML à ajouter. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | [System::String](../../../system/string/) | Une URI du HTML spécifié. Utilisée pour résoudre les liens relatifs. |
| useSlideWithIndexAsStart | **bool** | Ce drapeau détermine comment démarrer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index spécifié. Si **true**, l'insertion des données commencera dans un espace vide de la diapositive indiquée. Si **false**, les données seront ajoutées aux diapositives créées. |

### Valeur de retour

Diapositives ajoutées.

## SlideCollection::InsertFromHtml(int32_t, System::String) méthode


Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position d'insertion. |
| htmlText | [System::String](../../../system/string/) | HTML à ajouter. |

### Valeur de retour

Diapositives ajoutées

## SlideCollection::InsertFromHtml(int32_t, System::String, bool) méthode


Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position d'insertion. |
| htmlText | [System::String](../../../system/string/) | HTML à ajouter. |
| useSlideWithIndexAsStart | **bool** | Ce drapeau détermine comment démarrer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index spécifié. Si **true**, l'insertion des données commencera dans un espace vide de la diapositive indiquée. Si **false**, les données seront ajoutées aux diapositives créées. |

### Valeur de retour

Diapositives ajoutées

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) méthode


Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position d'insertion. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objet TextReader qui sera utilisé comme source d'un fichier HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | [System::String](../../../system/string/) | Une URI du HTML spécifié. Utilisée pour résoudre les liens relatifs. |

### Valeur de retour

Diapositives ajoutées.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) méthode


Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position d'insertion. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objet TextReader qui sera utilisé comme source d'un fichier HTML. |

### Valeur de retour

Diapositives ajoutées

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) méthode


Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position d'insertion. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | [System::String](../../../system/string/) | Une URI du HTML spécifié. Utilisée pour résoudre les liens relatifs. |

### Valeur de retour

Diapositives ajoutées.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) méthode


Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position d'insertion. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | [System::String](../../../system/string/) | Une URI du HTML spécifié. Utilisée pour résoudre les liens relatifs. |
| useSlideWithIndexAsStart | **bool** | Ce drapeau détermine comment démarrer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index spécifié. Si **true**, l'insertion des données commencera dans un espace vide de la diapositive indiquée. Si **false**, les données seront ajoutées aux diapositives créées. |

### Valeur de retour

Diapositives ajoutées.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) méthode


Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position d'insertion. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |

### Valeur de retour

Diapositives ajoutées

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) méthode


Crée des diapositives à partir du texte HTML et les insère dans la collection à la position spécifiée.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Position d'insertion. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un objet Stream qui sera utilisé comme source d'un fichier HTML. |
| useSlideWithIndexAsStart | **bool** | Ce drapeau détermine comment démarrer l'insertion : à partir d'une nouvelle diapositive ou à partir de la diapositive avec l'index spécifié. Si **true**, l'insertion des données commencera dans un espace vide de la diapositive indiquée. Si **false**, les données seront ajoutées aux diapositives créées. |

### Valeur de retour

Diapositives ajoutées

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Class [SlideCollection](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)