---
title: WriteAsEmf()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Ukládá obsah snímku jako soubor EMF.
type: docs
weight: 170
url: /cs/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) metoda


Ukládá obsah snímku jako soubor EMF.

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Cílový stream |
## Poznámky



Následující ukázkový kód demonstruje, jak převést první snímek z prezentace PowerPoint do metafilu. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// Uloží první snímek jako metafil
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Stream](../../../system.io/stream/)
* Třída [Slide](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)