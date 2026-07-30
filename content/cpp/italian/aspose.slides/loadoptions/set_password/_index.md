---
title: set_Password()
second_title: Riferimento API Aspose.Slides per C++
description: "Imposta la password. Scrivi System::String."
type: docs
weight: 118
url: /it/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) metodo

Sets the password. Write [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## Osservazioni

La password. 

Il seguente codice di esempio mostra come aprire PowerPoint protetto da password [Presentation](../../presentation/). 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [LoadOptions](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)