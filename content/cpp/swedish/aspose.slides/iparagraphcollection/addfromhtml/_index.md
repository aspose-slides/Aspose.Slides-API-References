---
title: AddFromHtml()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till text från angiven HTML-sträng till samlingen.
type: docs
weight: 92
url: /sv/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) metod

Lägger till text från angiven HTML-sträng till samlingen.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML-text. |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metod

Lägger till text från angiven HTML-sträng till samlingen.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML-text. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Resolver callback-objekt som löser URI:er och hämtar refererade objekt. |
| uri | [System::String](../../../system/string/) | URI för att lägga till HTML-dokument. Används för att lösa relativa länkar. |

## Anmärkningar

Att specificera resolver kan potentiellt introducera en vulnurability. Använd med försiktighet.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [IParagraphCollection](../)
* Klass [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)