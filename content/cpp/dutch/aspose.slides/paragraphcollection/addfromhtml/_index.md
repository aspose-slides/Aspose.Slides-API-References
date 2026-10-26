---
title: AddFromHtml()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt tekst toe van de opgegeven html-string aan de collectie.
type: docs
weight: 157
url: /nl/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) methode


Voegt tekst toe van de opgegeven html-string aan de collectie.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML-tekst. |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) methode


Voegt tekst toe van de opgegeven html-string aan de collectie.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML-tekst. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Resolver-callback-object dat URI's oplost en verwijzende objecten ophaalt. |
| uri | [System::String](../../../system/string/) | URI voor het toevoegen van een HTML-document. Gebruikt voor het oplossen van relatieve koppelingen. |
## Opmerkingen



Het specificeren van een resolver kan mogelijk een kwetsbaarheid introduceren. Gebruik met voorzichtigheid.
## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [ParagraphCollection](../)
* Klasse [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)