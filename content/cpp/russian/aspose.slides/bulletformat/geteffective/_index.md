---
title: GetEffective()
second_title: Aspose.Slides для C++ справка API
description: Получает данные эффективного форматирования маркеров с применённым наследованием.
type: docs
weight: 248
url: /ru/aspose.slides/bulletformat/geteffective/
---
## BulletFormat::GetEffective() метод

Получает данные эффективного форматирования маркеров с применённым наследованием.

```cpp
System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::BulletFormat::GetEffective() override
```

### Возвращаемое значение

Экземпляр [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## Примечания

Этот пример демонстрирует получение некоторых свойств эффективного формата маркера. 
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<Aspose::Slides::IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveBulletFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_Bullet()->GetEffective();

Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveBulletFormat->get_Type()));
if (effectiveBulletFormat->get_Type() == Aspose::Slides::BulletType::Numbered)
{
    Console::WriteLine(String(u"Numbered style: ") + ObjectExt::ToString(effectiveBulletFormat->get_NumberedBulletStyle()));
    Console::WriteLine(String(u"Starting number: ") + effectiveBulletFormat->get_NumberedBulletStartWith());
}
```

## См. также

* typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* Класс [BulletFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)