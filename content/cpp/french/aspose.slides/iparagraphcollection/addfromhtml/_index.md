---
title: AddFromHtml()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute du texte provenant d'une chaîne HTML spécifiée à la collection.
type: docs
weight: 92
url: /fr/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) method

Ajoute du texte provenant d’une chaîne HTML spécifiée à la collection.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | texte HTML. |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Ajoute du texte provenant d’une chaîne HTML spécifiée à la collection.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | texte HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | objet de rappel du résolveur qui résout les URI et récupère les objets référencés. |
| uri | [System::String](../../../system/string/) | URI pour ajouter le document HTML. Utilisé pour résoudre les liens relatifs. |
## Remarks

Spécifier un résolveur peut potentiellement introduire une vulnérabilité. Utilisez-le avec prudence.
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [IParagraphCollection](../)
* Classe [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)