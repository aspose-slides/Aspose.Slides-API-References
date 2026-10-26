---
title: get_Traces()
second_title: Aspose.Slides для C++ справочник API
description: Получает все трассы, содержащиеся в элементе IInk IInkTrace. Только для чтения.
type: docs
weight: 1
url: /ru/aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() method


Получает все трассы, содержащиеся в элементе [IInk](../../iink/) [IInkTrace](../../iinktrace/). Только для чтения.

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IInkTrace](../../iinktrace/)
* Класс [Ink](../)
* Пространство имён [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)