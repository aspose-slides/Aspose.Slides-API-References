---
title: ToBox()
second_title: Aspose.Slides för C++ API-referens
description: Placera detta element i en icke-visuell låda (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text. Ett inneslutet objekt kan (till exempel) fungera som en operator-emulator med eller utan en justeringspunkt, fungera som en radbrytningspunkt, eller grupperas så att radbrytningar inte tillåts inom.
type: docs
weight: 261
url: /sv/aspose.slides.mathtext/mathelementbase/tobox/
---
## MathElementBase::ToBox() metod


Placera detta element i en icke-visuell låda (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text. Ett inneslutet objekt kan (till exempel) fungera som en operator-emulator med eller utan en justeringspunkt, fungera som en radbrytningspunkt, eller grupperas så att radbrytningar inte tillåts inom.

```cpp
System::SharedPtr<IMathBox> Aspose::Slides::MathText::MathElementBase::ToBox() override
```


### Returvärde

Logisk låda med detta element placerat inuti
## Anmärkningar



Exempel: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathBox](../../imathbox/)
* Klass [MathElementBase](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)