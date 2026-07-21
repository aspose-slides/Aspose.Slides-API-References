---
title: get_RefreshThumbnail()
second_title: Aspose.Slides для C++: справочник API
description: Указывает, будет ли обновляться миниатюра презентации. Читается bool. Значение по умолчанию — true.
type: docs
weight: 53
url: /ru/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() метод


Указывает, будет ли обновляться миниатюра презентации. Читается **bool**. Значение по умолчанию — **true**.

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
```

## Примечания


Когда значение параметра равно **true**, будет сгенерирована новая миниатюра.

Когда значение параметра равно **false**, текущая миниатюра будет сохранена без изменений.

Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## См. также

* Класс [IPptxOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)