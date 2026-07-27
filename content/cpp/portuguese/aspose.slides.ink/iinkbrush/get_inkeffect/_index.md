---
title: get_InkEffect()
second_title: Referência da API Aspose.Slides para C++
description: "Obtém o tipo de efeito de tinta (por exemplo, Galaxy, Gold, Silver) que define o estilo visual da linha de tinta. O valor é analisado a partir da propriedade do pincel \"inkEffects\". Se nenhum efeito reconhecido for especificado, InkEffectType::NotDefined é retornado."
type: docs
weight: 53
url: /pt/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() método


Obtém o tipo de efeito de tinta (por exemplo, Galaxy, Gold, Silver) que define o estilo visual do traço de tinta. O valor é analisado a partir da propriedade do pincel \"inkEffects\". Se nenhum efeito reconhecido for especificado, [InkEffectType::NotDefined](../../inkeffecttype/) é retornado.

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## Veja Também

* Enum [InkEffectType](../../inkeffecttype/)
* Class [IInkBrush](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)