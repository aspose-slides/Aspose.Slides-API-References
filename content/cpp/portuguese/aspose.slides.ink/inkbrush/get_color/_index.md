---
title: get_Color()
second_title: Referência da API Aspose.Slides para C++
description: Obtém a cor do pincel para uma linha.
type: docs
weight: 1
url: /pt/aspose.slides.ink/inkbrush/get_color/
---
## InkBrush::get_Color() método


Obtém a cor do pincel para uma linha.

```cpp
System::Drawing::Color Aspose::Slides::Ink::InkBrush::get_Color() override
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
* Classe [InkBrush](../)
* Espaço de nomes [Aspose::Slides::Ink](../../)
* Biblioteca [Aspose.Slides](../../../)