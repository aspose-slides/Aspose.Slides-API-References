---
title: set_Size()
second_title: Referência da API Aspose.Slides para C++
description: Define o tamanho do pincel para uma linha em pontos.
type: docs
weight: 40
url: /pt/aspose.slides.ink/inkbrush/set_size/
---
## InkBrush::set_Size(System::Drawing::SizeF) method


Define o tamanho do pincel para uma linha em pontos.

```cpp
void Aspose::Slides::Ink::InkBrush::set_Size(System::Drawing::SizeF value) override
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## Veja Também

* Classe [SizeF](../../../system.drawing/sizef/)
* Classe [InkBrush](../)
* Namespace [Aspose::Slides::Ink](../../)
* Biblioteca [Aspose.Slides](../../../)