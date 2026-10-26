---
title: set_RefreshThumbnail()
second_title: Справка API Aspose.Slides для C++
description: Указывает, будет ли обновляться миниатюра презентации. Запись bool. Значение по умолчанию — true.
type: docs
weight: 66
url: /ru/aspose.slides.export/pptxoptions/set_refreshthumbnail/
---
## PptxOptions::set_RefreshThumbnail(bool) метод

Указывает, будет ли обновляться миниатюра презентации. Записать **bool**. Значение по умолчанию — **true**.

```cpp
void Aspose::Slides::Export::PptxOptions::set_RefreshThumbnail(bool value) override
```

## Замечания

Когда значение опции **true**, будет создана новая миниатюра.

Когда значение опции **false**, текущая миниатюра будет сохранена без изменений.

Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Смотрите также

* Класс [PptxOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)