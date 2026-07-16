---
title: AddFromHtml()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute du texte à partir de la chaîne HTML spécifiée à la collection.
type: docs
weight: 157
url: /fr/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) méthode

Ajoute du texte à partir de la chaîne HTML spécifiée à la collection.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | texte HTML. |


## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) méthode

Ajoute du texte à partir de la chaîne HTML spécifiée à la collection.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | texte HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objet de rappel du résolveur qui résout les URI et récupère les objets référencés. |
| uri | [System::String](../../../system/string/) | URI pour l'ajout du document HTML. Utilisé pour résoudre les liens relatifs. |


## Remarques

Spécifier le résolveur peut potentiellement introduire une vulnérabilité. Utilisez-le avec prudence.


## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [ParagraphCollection](../)
* Classe [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)