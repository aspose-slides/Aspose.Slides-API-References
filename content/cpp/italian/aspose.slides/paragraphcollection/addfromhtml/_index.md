---
title: AddFromHtml()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge testo dalla stringa HTML specificata alla raccolta.
type: docs
weight: 157
url: /it/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) metodo

Aggiunge testo dalla stringa HTML specificata alla raccolta.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Testo HTML. |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metodo

Aggiunge testo dalla stringa HTML specificata alla raccolta.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Testo HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Oggetto callback del resolver che risolve gli URI e recupera gli oggetti referenziati. |
| uri | [System::String](../../../system/string/) | URI per aggiungere il documento HTML. Usato per risolvere i collegamenti relativi. |
## Osservazioni

Specificare il resolver può potenzialmente introdurre una vulnerabilità. Usare con cautela.
## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [ParagraphCollection](../)
* Classe [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)