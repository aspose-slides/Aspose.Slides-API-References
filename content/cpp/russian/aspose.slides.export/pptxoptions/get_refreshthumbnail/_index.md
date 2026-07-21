---
title: get_RefreshThumbnail()
second_title: Aspose.Slides для C++: справка по API
description: Указывает, будет ли обновлена миниатюра презентации. Читается bool. Значение по умолчанию — true.
type: docs
weight: 53
url: /ru/aspose.slides.export/pptxoptions/get_refreshthumbnail/
---
## PptxOptions::get_RefreshThumbnail() метод


Указывает, будет ли обновлен миниатюра презентации. Читается **bool**. Значение по умолчанию - **true**.

```cpp
bool Aspose::Slides::Export::PptxOptions::get_RefreshThumbnail() override
```

## Примечания


Когда значение параметра равно **true**, будет создана новая миниатюра.

Когда значение параметра равно **false**, текущая миниатюра будет сохранена как есть.

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