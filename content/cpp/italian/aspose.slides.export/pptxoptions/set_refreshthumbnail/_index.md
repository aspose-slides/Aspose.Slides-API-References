---
title: set_RefreshThumbnail()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica se la miniatura della presentazione sarà aggiornata. Scrivi bool. Il valore predefinito è true.
type: docs
weight: 66
url: /it/aspose.slides.export/pptxoptions/set_refreshthumbnail/
---
## PptxOptions::set_RefreshThumbnail(bool) metodo


Specifica se la miniatura della presentazione verrà aggiornata. Scrivi **bool**. Il valore predefinito è **true**.

```cpp
void Aspose::Slides::Export::PptxOptions::set_RefreshThumbnail(bool value) override
```

## Osservazioni


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

* Classe [PptxOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)