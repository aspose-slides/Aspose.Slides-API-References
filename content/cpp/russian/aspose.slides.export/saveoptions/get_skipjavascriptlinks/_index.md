---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides для C++ — справочник API
description: Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Читается **bool**. Значение по умолчанию — **false**.
type: docs
weight: 105
url: /ru/aspose.slides.export/saveoptions/get_skipjavascriptlinks/
---
## SaveOptions::get_SkipJavaScriptLinks() метод


Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Читается **bool**. Значение по умолчанию — **false**.

```cpp
bool Aspose::Slides::Export::SaveOptions::get_SkipJavaScriptLinks() override
```

## Примечания


Если это свойство установлено в **true**, гиперссылки с вызовами JavaScript будут игнорироваться при сохранении.

Если это свойство установлено в **false**, все гиперссылки будут сохранены.

Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## См. также

* Класс [SaveOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)