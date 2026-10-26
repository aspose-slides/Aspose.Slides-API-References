---
title: WriteAsEmf()
second_title: Riferimento API Aspose.Slides per C++
description: Salva il contenuto della diapositiva come file EMF.
type: docs
weight: 170
url: /it/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) metodo


Salva il contenuto della diapositiva come file EMF.

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream di destinazione |
## Osservazioni



Il seguente esempio di codice dimostra come convertire la prima diapositiva di una presentazione PowerPoint in un metafile. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// Salva la prima diapositiva come metafile
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [Slide](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)