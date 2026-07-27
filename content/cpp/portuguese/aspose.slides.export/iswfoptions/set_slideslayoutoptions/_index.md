---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides para C++ Referência da API
description: Define o modo em que os slides são colocados na página ao exportar uma apresentação ISlidesLayoutOptions. Esta propriedade não suporta a atribuição de objetos do tipo Aspose.Slides.Export.HandoutLayoutingOptions
type: docs
weight: 404
url: /pt/aspose.slides.export/iswfoptions/set_slideslayoutoptions/
---
## ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) method

Define o modo em que os slides são colocados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../islideslayoutoptions/). Esta propriedade não suporta a atribuição de objetos do tipo **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)**

```cpp
virtual void Aspose::Slides::Export::ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
```

## Observações

Exemplo:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_CommentsPosition(CommentsPositions::Right);

System::SharedPtr<SwfOptions> options = System::MakeObject<SwfOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.swf", SaveFormat::Swf, options);
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Classe [ISwfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)