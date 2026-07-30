---
title: set_RefreshThumbnail()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica se la miniatura della presentazione verrà aggiornata. Scrivi bool. Il valore predefinito è true.
type: docs
weight: 66
url: /it/aspose.slides.export/ipptxoptions/set_refreshthumbnail/
---
## IPptxOptions::set_RefreshThumbnail(bool) metodo

Specifica se la miniatura della presentazione sarà aggiornata. Scrivi **bool**. Il valore predefinito è **true**.

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_RefreshThumbnail(bool value)=0
```

## Note

Quando il valore dell'opzione è **true**, verrà generata la nuova miniatura.

Quando il valore dell'opzione è **false**, la miniatura corrente verrà salvata così com'è.

Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Vedi anche

* Classe [IPptxOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)