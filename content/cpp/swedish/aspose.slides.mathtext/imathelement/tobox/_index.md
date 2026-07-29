---
title: ToBox()
second_title: Aspose.Slides för C++ API-referens
description: Placera detta element i en icke-visuell ruta (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text. Ett inramat objekt kan (till exempel) fungera som en operatoremulator med eller utan en justeringspunkt, fungera som en radbrytningspunkt, eller grupperas så att radbrytningar inte tillåts inom.
type: docs
weight: 274
url: /sv/aspose.slides.mathtext/imathelement/tobox/
---
## IMathElement::ToBox() metod


Placera detta element i en icke-visuell ruta (logisk gruppering) som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text. Ett inramat objekt kan (till exempel) fungera som en operatoremulator med eller utan en justeringspunkt, fungera som en radbrytningspunkt, eller grupperas så att radbrytningar inte tillåts inom.

```cpp
virtual System::SharedPtr<IMathBox> Aspose::Slides::MathText::IMathElement::ToBox()=0
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
* Klass [IMathElement](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)