---
title: set_SkipJavaScriptLinks()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. Scrivi **bool**. Il valore predefinito è **false**.
type: docs
weight: 118
url: /it/aspose.slides.export/isaveoptions/set_skipjavascriptlinks/
---
## ISaveOptions::set_SkipJavaScriptLinks(bool) metodo


Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. Scrivi **bool**. Il valore predefinito è **false**.

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_SkipJavaScriptLinks(bool value)=0
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

* Classe [ISaveOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)