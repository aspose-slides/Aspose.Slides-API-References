---
title: GetEffective()
second_title: Aspose.Slides для C++ API Reference
description: Получает данные эффективного форматирования части с учётом наследования.
type: docs
weight: 131
url: /ru/aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() method


Получает данные эффективного форматирования части с учётом наследования.

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```


### Возвращаемое значение

Объект [IPortionFormatEffectiveData](../../iportionformateffectivedata/).
## Замечания



В этом примере демонстрируется получение некоторых свойств эффективного форматирования части. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* Класс [PortionFormat](../)
* Пространство имен [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)