---
title: AddFromHtml()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till text från angiven HTML-sträng till samlingen.
type: docs
weight: 157
url: /sv/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) metod

Lägger till text från angiven HTML-sträng till samlingen.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML-text. |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metod

Lägger till text från angiven HTML-sträng till samlingen.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML-text. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Resolver-återuppringningsobjekt som löser URI:er och hämtar refererade objekt. |
| uri | [System::String](../../../system/string/) | URI för att lägga till HTML-dokument. Används för att lösa relativa länkar. |

## Anmärkningar

Att specificera resolver kan potentiellt introducera en sårbarhet. Använd med försiktighet.

## Se även

* Typdef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [ParagraphCollection](../)
* Klass [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)