---
title: WriteAsEmf()
second_title: Aspose.Slides för C++ API-referens
description: Sparar bildinnehållet som en EMF-fil.
type: docs
weight: 170
url: /sv/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) metod

Sparar bildinnehållet som en EMF-fil.

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Målsström |
## Anmärkningar

Följande kodexempel visar hur man konverterar den första bilden från en PowerPoint-presentation till en metafil.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// Sparar den första bilden som en metafil
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Slide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)