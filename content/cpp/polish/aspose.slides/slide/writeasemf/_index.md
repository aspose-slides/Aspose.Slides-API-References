---
title: WriteAsEmf()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zapisuje zawartość slajdu jako plik EMF.
type: docs
weight: 170
url: /pl/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) metoda

Zapisuje zawartość slajdu jako plik EMF.

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień docelowy |
## Uwagi

Poniższy przykład kodu demonstruje, jak przekonwertować pierwszy slajd prezentacji PowerPoint do metapliku.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// Zapisuje pierwszy slajd jako metaplik
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [Slide](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)