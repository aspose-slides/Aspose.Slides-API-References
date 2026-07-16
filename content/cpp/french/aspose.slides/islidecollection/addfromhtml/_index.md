---
title: AddFromHtml()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.
type: docs
weight: 144
url: /fr/aspose.slides/islidecollection/addfromhtml/
---
## ISlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) méthode

Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html à ajouter. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | [System::String](../../../system/string/) | Une URI du HTML spécifié. Utilisée pour résoudre les liens relatifs. |

### Valeur de retour

Diapositives ajoutées.

## ISlideCollection::AddFromHtml(System::String) méthode

Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html à ajouter. |

### Valeur de retour

Diapositives ajoutées

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) méthode

Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objet TextReader qui sera utilisé comme source d'un fichier HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | [System::String](../../../system/string/) | Une URI du HTML spécifié. Utilisée pour résoudre les liens relatifs. |

### Valeur de retour

Diapositives ajoutées.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) méthode

Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objet TextReader qui sera utilisé comme source d'un fichier HTML. |

### Valeur de retour

Diapositives ajoutées

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) méthode

Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objet Stream qui sera utilisé comme source d'un fichier HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est null, tous les objets externes seront ignorés. |
| uri | [System::String](../../../system/string/) | Une URI du HTML spécifié. Utilisée pour résoudre les liens relatifs. |

### Valeur de retour

Diapositives ajoutées.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) méthode

Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objet Stream qui sera utilisé comme source d'un fichier HTML. |

### Valeur de retour

Diapositives ajoutées

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [String](../../../system/string/)
* Classe [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Classe [ISlideCollection](../)
* Classe [TextReader](../../../system.io/textreader/)
* Classe [Stream](../../../system.io/stream/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)