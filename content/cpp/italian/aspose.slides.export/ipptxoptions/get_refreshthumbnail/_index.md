---
title: get_RefreshThumbnail()
second_title: Riferimento API Aspose.Slides per C++
description: Specifica se la miniatura della presentazione verrà aggiornata. Lettura bool. Il valore predefinito è true.
type: docs
weight: 53
url: /it/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() metodo

Specifica se la miniatura della presentazione verrà aggiornata. Lettura **bool**. Il valore predefinito è **true**.

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
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

* Classe [IPptxOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)