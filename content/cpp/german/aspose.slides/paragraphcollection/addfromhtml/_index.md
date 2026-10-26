---
title: AddFromHtml()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt Text aus einer angegebenen HTML-Zeichenfolge zur Sammlung hinzu.
type: docs
weight: 157
url: /de/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) Methode

Fügt Text aus einer angegebenen HTML-Zeichenfolge zur Sammlung hinzu.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML-Text. |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) Methode

Fügt Text aus einer angegebenen HTML-Zeichenfolge zur Sammlung hinzu.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML-Text. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Resolver-Callback-Objekt, das URIs auflöst und referenzierte Objekte abruft. |
| uri | [System::String](../../../system/string/) | URI zum Hinzufügen eines HTML-Dokuments. Wird zum Auflösen relativer Links verwendet. |

## Bemerkungen

Das Angeben eines Resolvers kann potenziell eine Sicherheitslücke einführen. Verwenden Sie es mit Vorsicht.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [ParagraphCollection](../)
* Klasse [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)