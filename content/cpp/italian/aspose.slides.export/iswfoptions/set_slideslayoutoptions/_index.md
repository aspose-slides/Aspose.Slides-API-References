---
title: set_SlidesLayoutOptions()
second_title: Riferimento API Aspose.Slides per C++
description: Imposta la modalità con cui le diapositive vengono posizionate sulla pagina durante l'esportazione di una presentazione ISlidesLayoutOptions. Questa proprietà non supporta l'assegnazione di oggetti di tipo Aspose.Slides.Export.HandoutLayoutingOptions
type: docs
weight: 404
url: /it/aspose.slides.export/iswfoptions/set_slideslayoutoptions/
---
## ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) metodo

Imposta la modalità in cui le diapositive vengono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../islideslayoutoptions/). Questa proprietà non supporta l'assegnazione di oggetti di tipo **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)**

```cpp
virtual void Aspose::Slides::Export::ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
```

## Osservazioni

Esempio:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_CommentsPosition(CommentsPositions::Right);

System::SharedPtr<SwfOptions> options = System::MakeObject<SwfOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.swf", SaveFormat::Swf, options);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [ISlidesLayoutOptions](../../islideslayoutoptions/)
* classe [ISwfOptions](../)
* spazio dei nomi [Aspose::Slides::Export](../../)
* libreria [Aspose.Slides](../../../)