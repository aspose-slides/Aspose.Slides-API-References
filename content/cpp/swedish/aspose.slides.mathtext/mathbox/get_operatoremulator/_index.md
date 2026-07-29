---
title: get_OperatorEmulator()
second_title: Aspose.Slides för C++ API-referens
description: "Operator Emulator. När true, rutan och dess innehåll beter sig som en enda operator och ärver egenskaperna hos en operator. Detta betyder till exempel att tecknet kan fungera som en punkt för en radbrytning och kan justeras till andra operatorer. Operator Emulators används ofta när en eller flera glyfer kombineras för att bilda en operator, såsom '=='. Standardvärde: false"
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/mathbox/get_operatoremulator/
---
## MathBox::get_OperatorEmulator() metod


Operator Emulator. När true, rutan och dess innehåll beter sig som en enda operator och ärver egenskaperna från en operator. Detta innebär till exempel att tecknet kan fungera som en punkt för en radbrytning och kan justeras till andra operatorer. Operator Emulators används ofta när en eller flera glyfer kombineras för att bilda en operator, såsom '=='. Standardvärde: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_OperatorEmulator() override
```

## Anmärkningar


Exempel: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## Se också

* Klass [MathBox](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)