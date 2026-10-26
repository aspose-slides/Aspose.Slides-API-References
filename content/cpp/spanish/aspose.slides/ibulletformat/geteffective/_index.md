---
title: GetEffective()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene los datos de formato de viñeta efectivos con la herencia aplicada.
type: docs
weight: 248
url: /es/aspose.slides/ibulletformat/geteffective/
---
## IBulletFormat::GetEffective() method

Obtiene los datos de formato de viñeta efectivos con la herencia aplicada.

```cpp
virtual System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::IBulletFormat::GetEffective()=0
```

### Valor devuelto

Un [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## Observaciones

Este ejemplo muestra cómo obtener algunas propiedades de formato de viñeta efectivos. 
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

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* Clase [IBulletFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)