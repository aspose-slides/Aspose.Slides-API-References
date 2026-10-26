---
title: GetEffective()
second_title: Aspose.Slides для C++ справочник API
description: Получает данные эффективного форматирования линии с применённым наследованием.
type: docs
weight: 417
url: /ru/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() метод

Получает данные эффективного форматирования линии с применённым наследованием.

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```

### Возвращаемое значение

[ILineFormatEffectiveData](../../ilineformateffectivedata/).

## Примечания

Этот пример демонстрирует получение эффективных свойств формата линии фигуры.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## Смотрите также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* Класс [LineFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)