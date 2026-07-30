---
title: AddFromHtml()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge testo dalla stringa HTML specificata alla collezione.
type: docs
weight: 92
url: /it/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) metodo

Aggiunge testo dalla stringa HTML specificata alla collezione.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Testo HTML. |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metodo

Aggiunge testo dalla stringa HTML specificata alla collezione.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Testo HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Oggetto callback del risolutore che risolve gli URI e recupera gli oggetti referenziati. |
| uri | [System::String](../../../system/string/) | URI per aggiungere il documento HTML. Utilizzato per risolvere i collegamenti relativi. |

## Osservazioni

Specificare il risolutore può potenzialmente introdurre una vulnerabilità. Usare con cautela.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [IParagraphCollection](../)
* Classe [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)