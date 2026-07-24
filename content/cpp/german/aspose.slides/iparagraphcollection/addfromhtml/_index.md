---
title: AddFromHtml()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt Text aus einer angegebenen HTML-Zeichenfolge zur Sammlung hinzu.
type: docs
weight: 92
url: /de/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) method

Fügt Text aus einer angegebenen HTML-Zeichenfolge zur Sammlung hinzu.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML-Text. |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Fügt Text aus einer angegebenen HTML-Zeichenfolge zur Sammlung hinzu.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML-Text. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Resolver-Callback-Objekt, das URIs auflöst und referenzierte Objekte abruft. |
| uri | [System::String](../../../system/string/) | URI zum Hinzufügen des HTML-Dokuments. Wird zum Auflösen relativer Links verwendet. |

## Bemerkungen

Das Angeben eines Resolvers kann potenziell eine Sicherheitslücke einführen. Mit Vorsicht verwenden.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [IParagraphCollection](../)
* Klasse [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)