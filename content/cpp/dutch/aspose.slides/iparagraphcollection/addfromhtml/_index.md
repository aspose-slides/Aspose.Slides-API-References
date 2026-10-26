---
title: AddFromHtml()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt tekst toe vanuit een gespecificeerde html-string aan de collectie.
type: docs
weight: 92
url: /nl/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) methode


Voegt tekst toe vanuit een gespecificeerde html-string aan de collectie.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML-tekst. |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) methode


Voegt tekst toe vanuit een gespecificeerde html-string aan de collectie.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML-tekst. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Resolver-callback-object dat URI’s oplost en verwezen objecten ophaalt. |
| uri | [System::String](../../../system/string/) | URI voor het toevoegen van het HTML-document. Wordt gebruikt voor het oplossen van relatieve koppelingen. |
## Opmerkingen



Het specificeren van de resolver kan mogelijk een kwetsbaarheid introduceren. Gebruik met voorzichtigheid.
## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [IParagraphCollection](../)
* Klasse [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)