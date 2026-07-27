---
title: set_Color()
second_title: Referência da API Aspose.Slides para C++
description: Define a cor do pincel para uma linha.
type: docs
weight: 14
url: /pt/aspose.slides.ink/iinkbrush/set_color/
---
## IInkBrush::set_Color(System::Drawing::Color) método

Define a cor do pincel para uma linha.

```cpp
virtual void Aspose::Slides::Ink::IInkBrush::set_Color(System::Drawing::Color value)=0
```

## Observações

Exemplo:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## Ver também

* Classe [Color](../../../system.drawing/color/)
* Classe [IInkBrush](../)
* Espaço de nomes [Aspose::Slides::Ink](../../)
* Biblioteca [Aspose.Slides](../../../)