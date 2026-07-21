---
title: WriteAsEmf()
second_title: Aspose.Slides для C++ справочник API
description: Сохраняет содержимое слайда в виде файла EMF.
type: docs
weight: 170
url: /ru/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) метод

Сохраняет содержимое слайда в виде файла EMF.

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Целевой поток |
## Примечания

Следующий пример кода демонстрирует, как преобразовать первый слайд из презентации PowerPoint в метафайл. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// Сохраняет первый слайд как метафайл
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Slide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)