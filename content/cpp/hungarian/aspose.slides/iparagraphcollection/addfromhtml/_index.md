---
title: AddFromHtml()
second_title: Aspose.Slides C++ API hivatkozás
description: A megadott HTML karakterláncból szöveget ad a gyűjteményhez.
type: docs
weight: 92
url: /hu/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) metódus

A megadott HTML karakterláncból szöveget ad a gyűjteményhez.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML szöveg. |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metódus

A megadott HTML karakterláncból szöveget ad a gyűjteményhez.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML szöveg. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Resolver visszahívási objektum, amely feloldja az URI-kat és lekéri a hivatkozott objektumokat. |
| uri | [System::String](../../../system/string/) | HTML dokumentum hozzáadásához használt URI. Relatív linkek feloldásához használják. |

## Megjegyzések

A resolver megadása potenciálisan sebezhetőséget okozhat. Óvatosan használja.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [IParagraphCollection](../)
* Osztály [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)