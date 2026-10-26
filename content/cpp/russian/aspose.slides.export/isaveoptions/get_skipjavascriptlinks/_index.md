---
title: get_SkipJavaScriptLinks()
second_title: Справочник API Aspose.Slides для C++
description: Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Читает bool. Значение по умолчанию — false.
type: docs
weight: 105
url: /ru/aspose.slides.export/isaveoptions/get_skipjavascriptlinks/
---
## ISaveOptions::get_SkipJavaScriptLinks() метод

Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Читает **bool**. Значение по умолчанию — **false**.

```cpp
virtual bool Aspose::Slides::Export::ISaveOptions::get_SkipJavaScriptLinks()=0
```

## Примечания

Когда свойство установлено в **true**, гиперссылки с вызовами JavaScript будут игнорироваться при сохранении.

Когда свойство установлено в **false**, все гиперссылки будут сохранены.

Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Смотрите также

* Класс [ISaveOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)