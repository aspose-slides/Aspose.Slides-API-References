---
title: AddFromHtml()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Dodaje tekst z określonego ciągu HTML do kolekcji.
type: docs
weight: 92
url: /pl/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) metoda

Dodaje tekst z określonego ciągu HTML do kolekcji.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Tekst HTML. |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metoda

Dodaje tekst z określonego ciągu HTML do kolekcji.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Tekst HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Obiekt wywołania zwrotnego resolvera, który rozwiązuje URI i pobiera odwoływane obiekty. |
| uri | [System::String](../../../system/string/) | URI używane przy dodawaniu dokumentu HTML. Używane do rozwiązywania względnych odnośników. |
## Uwagi

Określenie resolvera może wprowadzić podatność. Należy używać ostrożnie.
## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [IParagraphCollection](../)
* Klasa [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)