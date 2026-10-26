---
title: set_OperatorEmulator()
second_title: Aspose.Slides för C++ API-referens
description: "Operatoremulator. När true, beter lådan och dess innehåll sig som en enda operator och ärver egenskaperna hos en operator. Detta innebär till exempel att tecknet kan fungera som en punkt för ett radbrytning och kan justeras mot andra operatorer. Operatoremulatorer används ofta när ett eller flera glyfer kombineras för att bilda en operator, såsom '=='. Standardvärde: false"
type: docs
weight: 27
url: /sv/aspose.slides.mathtext/mathbox/set_operatoremulator/
---
## MathBox::set_OperatorEmulator(bool) metod


Operatoremulator. När true, beter lådan och dess innehåll sig som en enda operator och ärver egenskaperna hos en operator. Detta innebär till exempel att tecknet kan fungera som en punkt för ett radbrytning och kan justeras mot andra operatorer. Operatoremulatorer används ofta när ett eller flera glyfer kombineras för att bilda en operator, såsom '=='. Standardvärde: false

```cpp
void Aspose::Slides::MathText::MathBox::set_OperatorEmulator(bool value) override
```

## Anmärkningar


Exempel:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## Se även

* Klass [MathBox](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)