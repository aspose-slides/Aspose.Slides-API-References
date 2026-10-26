---
title: AddFromHtml()
second_title: Aspose.Slides dla C++ Referencja API
description: Dodaje tekst z określonego ciągu HTML do kolekcji.
type: docs
weight: 157
url: /pl/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) metoda

Dodaje tekst z określonego ciągu HTML do kolekcji.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | tekst HTML. |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metoda

Dodaje tekst z określonego ciągu HTML do kolekcji.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | tekst HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Obiekt wywołania zwrotnego Resolver, który rozwiązuje URI i pobiera odwołane obiekty. |
| uri | [System::String](../../../system/string/) | URI używany do dodania dokumentu HTML. Służy do rozwiązywania linków względnych. |

## Uwagi

Określenie resolvera może potencjalnie wprowadzić podatność. Należy używać ostrożnie.

## Zobacz również

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [ParagraphCollection](../)
* Klasa [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)