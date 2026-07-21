---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides для C++: справочник API
description: Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Записывается bool. Значение по умолчанию — false.
type: docs
weight: 118
url: /ru/aspose.slides.export/saveoptions/set_skipjavascriptlinks/
---
## SaveOptions::set_SkipJavaScriptLinks(bool) метод


Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Записывается **bool**. Значение по умолчанию — **false**.

```cpp
void Aspose::Slides::Export::SaveOptions::set_SkipJavaScriptLinks(bool value) override
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
* Пространство имен [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)