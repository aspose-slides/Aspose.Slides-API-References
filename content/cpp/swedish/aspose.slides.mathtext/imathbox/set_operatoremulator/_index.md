---
title: set_OperatorEmulator()
second_title: Aspose.Slides för C++ API-referens
description: "Operatoremulator. När sant beter sig rutan och dess innehåll som en enda operator och ärver egenskaperna hos en operator. Detta innebär till exempel att tecknet kan fungera som en punkt för ett radbryt och kan justeras mot andra operatorer. Operatoremulatorer används ofta när en eller flera glyfer kombineras för att bilda en operator, till exempel '=='. Standardvärde: false"
type: docs
weight: 27
url: /sv/aspose.slides.mathtext/imathbox/set_operatoremulator/
---
## IMathBox::set_OperatorEmulator(bool) metod


Operatoremulator. När värdet är true beter sig boxen och dess innehåll som en enda operator och ärver egenskaperna hos en operator. Detta innebär till exempel att tecknet kan fungera som en punkt för ett radbryt och kan justeras mot andra operatorer. Operatoremulatorer används ofta när en eller flera glyfer kombineras för att bilda en operator, till exempel '=='. Standardvärde: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_OperatorEmulator(bool value)=0
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