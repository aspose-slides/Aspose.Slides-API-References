---
title: WriteAsEmf()
second_title: Aspose.Slides C++ API referencia
description: A diák tartalmát EMF fájlként menti.
type: docs
weight: 170
url: /hu/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) method


Mentse a diátartalmat EMF fájlként.

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```


### Paraméterek

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Célfolyam |
## Megjegyzések



Az alábbi kódpélda bemutatja, hogyan lehet a PowerPoint előadás első diaját metafájlra konvertálni. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// Az első diát metafájlba menti
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [Slide](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)