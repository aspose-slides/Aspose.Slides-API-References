---
title: AddFromHtml()
second_title: Aspose.Slides pro referenci API C++
description: Přidá text ze zadaného řetězce HTML do kolekce.
type: docs
weight: 157
url: /cs/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) method

Přidá text ze zadaného řetězce HTML do kolekce.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML text. |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Přidá text ze zadaného řetězce HTML do kolekce.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML text. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objekt zpětného volání resolveru, který řeší URI a načítá odkazované objekty. |
| uri | [System::String](../../../system/string/) | URI pro přidání dokumentu HTML. Používá se k řešení relativních odkazů. |

## Poznámky

Určení resolveru může potenciálně představovat zranitelnost. Používejte opatrně.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [ParagraphCollection](../)
* Třída [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)