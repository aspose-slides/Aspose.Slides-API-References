---
title: RemoveUnusedMasterSlides()
second_title: Aspose.Slides для C++: справочник API
description: Выполняет сжатие презентации путем удаления неиспользуемых мастер-слайдов.
type: docs
weight: 1
url: /ru/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## Compress::RemoveUnusedMasterSlides(System::SharedPtr\<Presentation\>) метод

Выполняет сжатие [Presentation](../../../aspose.slides/presentation/) путем удаления неиспользуемых мастер-слайдов.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedMasterSlides(System::SharedPtr<Presentation> pres)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Экземпляр презентации |
## Примечания

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Presentation](../../../aspose.slides/presentation/)
* Класс [Compress](../)
* Пространство имён [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)