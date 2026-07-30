---
title: AddFromHtml()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá text ze zadaného řetězce HTML do kolekce.
type: docs
weight: 92
url: /cs/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) metoda

Přidá text ze zadaného řetězce HTML do kolekce.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML text. |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metoda

Přidá text ze zadaného řetězce HTML do kolekce.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML text. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objekt zpětného volání resolveru, který řeší URI a načítá odkazované objekty. |
| uri | [System::String](../../../system/string/) | URI pro přidání HTML dokumentu. Používá se pro řešení relativních odkazů. |

## Poznámky

Zadání resolveru může potenciálně vytvořit zranitelnost. Používejte s opatrností.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [IParagraphCollection](../)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)