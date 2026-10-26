---
title: set_RefreshThumbnail()
second_title: Справочник API Aspose.Slides для C++
description: Указывает, будет ли миниатюра презентации обновлена. Записать bool. Значение по умолчанию — true.
type: docs
weight: 66
url: /ru/aspose.slides.export/ipptxoptions/set_refreshthumbnail/
---
## IPptxOptions::set_RefreshThumbnail(bool) метод

Указывает, будет ли миниатюра презентации обновлена. Записать **bool**. Значение по умолчанию — **true**.

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_RefreshThumbnail(bool value)=0
```

## Примечания

Когда значение параметра **true**, будет сгенерирована новая миниатюра.

Когда значение параметра **false**, текущая миниатюра будет сохранена как есть.

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