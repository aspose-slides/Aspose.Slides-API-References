---
title: set_Color()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta il colore del pennello per una linea.
type: docs
weight: 14
url: /it/aspose.slides.ink/inkbrush/set_color/
---
## InkBrush::set_Color(System::Drawing::Color) metodo


Imposta il colore del pennello per una linea.

```cpp
void Aspose::Slides::Ink::InkBrush::set_Color(System::Drawing::Color value) override
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