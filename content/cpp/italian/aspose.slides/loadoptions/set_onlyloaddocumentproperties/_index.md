---
title: set_OnlyLoadDocumentProperties()
second_title: Riferimento API di Aspose.Slides per C++
description: Questa proprietà è significativa se il file della presentazione è protetto da password. Il valore true indica che devono essere caricate solo le proprietà del documento da un file di presentazione crittografato e la password deve essere ignorata. Il valore false indica che l'intera presentazione crittografata deve essere caricata utilizzando la password corretta. Se la presentazione non è crittografata, il valore della proprietà è sempre ignorato. Se le proprietà del documento di un file crittografato non sono pubbliche e il valore della proprietà è true, le proprietà del documento non possono essere caricate e verrà sollevata un'eccezione. Scrivi bool.
type: docs
weight: 144
url: /it/aspose.slides/loadoptions/set_onlyloaddocumentproperties/
---
## LoadOptions::set_OnlyLoadDocumentProperties(bool) metodo

Questo attributo ha senso se il file della presentazione è protetto da password. Il valore true indica che solo le proprietà del documento devono essere caricate da un file di presentazione crittografato e la password deve essere ignorata. Il valore false indica che l'intera presentazione crittografata deve essere caricata utilizzando la password corretta. Se la presentazione non è crittografata, il valore della proprietà è sempre ignorato. Se le proprietà del documento di un file crittografato non sono pubbliche e il valore della proprietà è true, le proprietà del documento non possono essere caricate e verrà generata un'eccezione. Scrivi **bool**.

```cpp
void Aspose::Slides::LoadOptions::set_OnlyLoadDocumentProperties(bool value) override
```

## Vedi anche

* Classe [LoadOptions](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)