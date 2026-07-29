---
title: get_OperatorEmulator()
second_title: Aspose.Slides för C++ API-referens
description: "Operator Emulator. När sann beter lådan och dess innehåll sig som en enda operator och ärver egenskaperna hos en operator. Detta innebär till exempel att tecknet kan fungera som en plats för en radbrytning och kan justeras mot andra operatorer. Operator Emulatorer används ofta när en eller flera glyfer kombineras för att bilda en operator, såsom '=='. Standardvärde: false"
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/imathbox/get_operatoremulator/
---
## IMathBox::get_OperatorEmulator() metod


Operator Emulator. När sann, beter lådan och dess innehåll sig som en enda operator och ärver egenskaperna hos en operator. Detta innebär exempelvis att tecknet kan fungera som en plats för en radbrytning och kan justeras mot andra operatorer. Operator Emulatorer används ofta när en eller flera glyfer kombineras för att bilda en operator, såsom '=='. Standardvärde: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_OperatorEmulator()=0
```

## Anmärkningar


Exempel: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## Se även

* Klass [IMathBox](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)