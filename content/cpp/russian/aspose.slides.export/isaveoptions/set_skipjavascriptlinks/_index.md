---
title: set_SkipJavaScriptLinks()
second_title: Справочник API Aspose.Slides для C++
description: Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Тип bool. Значение по умолчанию — false.
type: docs
weight: 118
url: /ru/aspose.slides.export/isaveoptions/set_skipjavascriptlinks/
---
## ISaveOptions::set_SkipJavaScriptLinks(bool) метод


Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Тип **bool**. Значение по умолчанию — **false**.

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_SkipJavaScriptLinks(bool value)=0
```

## Примечания


Когда это свойство установлено в **true**, гиперссылки с вызовами JavaScript будут игнорироваться при сохранении.

Когда это свойство установлено в **false**, все гиперссылки будут сохранены.

Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## См. также

* Класс [ISaveOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)