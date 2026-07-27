---
title: get_FillFormat()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o formato de preenchimento da marcação de um parágrafo. Somente leitura IFillFormatEffectiveData.
type: docs
weight: 131
url: /pt/aspose.slides/ibulletformateffectivedata/get_fillformat/
---
## IBulletFormatEffectiveData::get_FillFormat() método

Retorna o formato de preenchimento da marcação de um parágrafo. Somente leitura [IFillFormatEffectiveData](../../ifillformateffectivedata/).

```cpp
virtual System::SharedPtr<IFillFormatEffectiveData> Aspose::Slides::IBulletFormatEffectiveData::get_FillFormat()=0
```

## Observações

Este exemplo demonstra como recuperar os dados efetivos de preenchimento da marcação. 
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>(u"SomePresentation.pptx");
// Presuma que a primeira forma no primeiro slide seja AutoShape com algum texto...
// Exiba informações sobre as marcas dos parágrafos de texto
auto autoShape = ExplicitCast<Aspose::Slides::AutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
for (auto para : IterateOver(autoShape->get_TextFrame()->get_Paragraphs()))
{
    auto bulletFormatEffective = para->get_ParagraphFormat()->get_Bullet()->GetEffective();
    Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(bulletFormatEffective->get_Type()));
    if (bulletFormatEffective->get_Type() != Aspose::Slides::BulletType::None)
    {
        Console::WriteLine(String(u"Bullet fill type: ") + ObjectExt::ToString(bulletFormatEffective->get_FillFormat()->get_FillType()));
        switch (bulletFormatEffective->get_FillFormat()->get_FillType())
        {
            case Aspose::Slides::FillType::Solid:
                Console::WriteLine(String(u"Solid fill color: ") + bulletFormatEffective->get_FillFormat()->get_SolidFillColor());
                break;

            case Aspose::Slides::FillType::Gradient:
            {
                Console::WriteLine(String(u"Gradient stops count: ") + bulletFormatEffective->get_FillFormat()->get_GradientFormat()->get_GradientStops()->get_Count());
                for (auto gradStop : IterateOver(bulletFormatEffective->get_FillFormat()->get_GradientFormat()->get_GradientStops()))
                {
                    Console::WriteLine(Convert::ToString(gradStop->get_Position()) + u": " + gradStop->get_Color());
                }
                break;
            }

            case Aspose::Slides::FillType::Pattern:
                Console::WriteLine(String(u"Pattern style: ") + ObjectExt::ToString(bulletFormatEffective->get_FillFormat()->get_PatternFormat()->get_PatternStyle()));
                Console::WriteLine(String(u"Fore color: ") + bulletFormatEffective->get_FillFormat()->get_PatternFormat()->get_ForeColor());
                Console::WriteLine(String(u"Back color: ") + bulletFormatEffective->get_FillFormat()->get_PatternFormat()->get_BackColor());
                break;

            default:
                break;
        }
    }
    Console::WriteLine();
}
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFillFormatEffectiveData](../../ifillformateffectivedata/)
* Classe [IBulletFormatEffectiveData](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)