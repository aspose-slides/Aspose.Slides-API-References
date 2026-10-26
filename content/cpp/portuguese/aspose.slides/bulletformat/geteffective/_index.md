---
title: GetEffective()
second_title: Referência da API Aspose.Slides para C++
description: Obtém os dados de formatação de marcadores efetivos com a herança aplicada.
type: docs
weight: 248
url: /pt/aspose.slides/bulletformat/geteffective/
---
## BulletFormat::GetEffective() método

Obtém os dados de formatação de marcadores efetivos com a herança aplicada.

```cpp
System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::BulletFormat::GetEffective() override
```

### Valor de Retorno

Um [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).

## Observações

Este exemplo demonstra como obter algumas propriedades de formato de marcadores efetivos.

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

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* Classe [BulletFormat](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)