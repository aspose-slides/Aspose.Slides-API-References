---
title: get_AllCustomXmlParts()
second_title: Aspose.Slides для справки API C++
description: Возвращает все пользовательские части данных в презентации. Только для чтения ICustomXmlPart[].
type: docs
weight: 287
url: /ru/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() метод

Возвращает все пользовательские части данных в презентации. Только для чтения [ICustomXmlPart](../../icustomxmlpart/)[].

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## Примечания

В следующих примерах показано, как очистить все пользовательские XML-части из PowerPoint [Presentation](../).
```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// Iterate all custom XML Parts
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## Смотрите также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [ICustomXmlPart](../../icustomxmlpart/)
* Класс [Presentation](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)