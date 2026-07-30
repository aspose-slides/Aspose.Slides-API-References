---
title: get_SkipJavaScriptLinks()
second_title: Riferimento API Aspose.Slides per C++
description: Specifica se ignorare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. Lettura bool. Il valore predefinito è false.
type: docs
weight: 105
url: /it/aspose.slides.export/saveoptions/get_skipjavascriptlinks/
---
## SaveOptions::get_SkipJavaScriptLinks() metodo


Specifica se ignorare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. Lettura **bool**. Il valore predefinito è **false**.

```cpp
bool Aspose::Slides::Export::SaveOptions::get_SkipJavaScriptLinks() override
```

## Osservazioni


Quando questa proprietà è impostata su **true**, i collegamenti ipertestuali con chiamate JavaScript verranno ignorati durante il salvataggio.

Quando questa proprietà è impostata su **false**, tutti i collegamenti ipertestuali verranno salvati.

Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Vedi anche

* Classe [SaveOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)