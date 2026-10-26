---
title: get_Traces()
second_title: Справочник API Aspose.Slides для C++
description: Получает все трассы, содержащиеся в элементе IInk IInkTrace. Только для чтения.
type: docs
weight: 1
url: /ru/aspose.slides.ink/iink/get_traces/
---
## IInk::get_Traces() method


Получает все трассы, содержащиеся в элементе [IInk](../) [IInkTrace](../../iinktrace/). Только для чтения.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::IInk::get_Traces()=0
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
* Класс [IInk](../)
* Пространство имён [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)