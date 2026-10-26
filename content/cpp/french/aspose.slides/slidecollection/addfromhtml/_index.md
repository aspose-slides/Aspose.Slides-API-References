---
title: AddFromHtml()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.
type: docs
weight: 196
url: /fr/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML à ajouter. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est nul, tous les objets externes seront ignorés. |
| uri | [System::String](../../../system/string/) | Une URI du HTML spécifié. Utilisée pour résoudre les liens relatifs. |

### Valeur de retour

Diapositives ajoutées.

## SlideCollection::AddFromHtml(System::String) method

Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML à ajouter. |

### Valeur de retour

Diapositives ajoutées

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objet TextReader qui sera utilisé comme source d'un fichier HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est nul, tous les objets externes seront ignorés. |
| uri | [System::String](../../../system/string/) | Une URI du HTML spécifié. Utilisée pour résoudre les liens relatifs. |

### Valeur de retour

Diapositives ajoutées.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) method

Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objet TextReader qui sera utilisé comme source d'un fichier HTML. |

### Valeur de retour

Diapositives ajoutées

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objet Stream qui sera utilisé comme source d'un fichier HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Un objet de rappel utilisé pour récupérer les objets externes. Si ce paramètre est nul, tous les objets externes seront ignorés. |
| uri | [System::String](../../../system/string/) | Une URI du HTML spécifié. Utilisée pour résoudre les liens relatifs. |

### Valeur de retour

Diapositives ajoutées.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) method

Crée des diapositives à partir du texte HTML et les ajoute à la fin de la collection.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objet Stream qui sera utilisé comme source d'un fichier HTML. |

### Valeur de retour

Diapositives ajoutées

## Remarques

```cpp
// Créer une instance de la classe Presentation.
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // Appeler la méthode AddFromHtml et transmettre le fichier HTML.
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// Utiliser la méthode Save pour enregistrer le fichier au format PowerPoint.
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [String](../../../system/string/)
* Classe [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Classe [SlideCollection](../)
* Classe [TextReader](../../../system.io/textreader/)
* Classe [Stream](../../../system.io/stream/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)