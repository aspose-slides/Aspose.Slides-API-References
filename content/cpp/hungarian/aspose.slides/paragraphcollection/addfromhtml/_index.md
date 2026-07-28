---
title: AddFromHtml()
second_title: Aspose.Slides C++ API hivatkozás
description: Szöveget ad a megadott HTML karakterláncból a gyűjteményhez.
type: docs
weight: 157
url: /hu/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) metódus

Szöveget ad hozzá a megadott html karakterláncból a gyűjteményhez.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML szöveg. |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metódus

Szöveget ad hozzá a megadott html karakterláncból a gyűjteményhez.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML szöveg. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Resolver visszahívási objektum, amely feloldja az URI-kat és letölti a hivatkozott objektumokat. |
| uri | [System::String](../../../system/string/) | URI a HTML dokumentum hozzáadásához. Relatív hivatkozások feloldásához használatos. |

## Megjegyzés

A resolver megadása potenciálisan sebezhetőséget hozhat be. Óvatosan használja.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ParagraphCollection](../)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)