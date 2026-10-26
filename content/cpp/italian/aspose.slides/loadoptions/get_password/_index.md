---
title: get_Password()
second_title: Riferimento API di Aspose.Slides per C++
description: "Ottiene la password. Leggi System::String."
type: docs
weight: 105
url: /it/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() metodo


Ottiene la password. Leggi [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## Osservazioni


La password. 

Il seguente codice di esempio mostra come aprire un PowerPoint protetto da password [Presentation](../../presentation/). 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// lavora con la presentazione decrittata
```

## Vedi anche

* classe [String](../../../system/string/)
* classe [LoadOptions](../)
* Spazio dei nomi [Aspose::Slides](../../)
* libreria [Aspose.Slides](../../../)