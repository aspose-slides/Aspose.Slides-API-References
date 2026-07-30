---
title: get_Color()
second_title: Aspose.Slides per C++ Riferimento API
description: Ottiene il colore del pennello per una linea.
type: docs
weight: 1
url: /it/aspose.slides.ink/inkbrush/get_color/
---
## InkBrush::get_Color() metodo

Ottiene il colore del pennello per una linea.

```cpp
System::Drawing::Color Aspose::Slides::Ink::InkBrush::get_Color() override
```

## Osservazioni

Esempio:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## Vedi anche

* Classe [Color](../../../system.drawing/color/)
* Classe [InkBrush](../)
* Spazio dei nomi [Aspose::Slides::Ink](../../)
* Libreria [Aspose.Slides](../../../)