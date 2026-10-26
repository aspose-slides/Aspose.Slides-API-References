---
title: set_HideDegree()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Skrýt stupeň. Když je true, stupeň se nezobrazuje, jako v \\u221A\\uD835\\uDC65
type: docs
weight: 40
url: /cs/aspose.slides.mathtext/imathradical/set_hidedegree/
---
## IMathRadical::set_HideDegree(bool) metoda


Skrýt stupeň. Když je true, stupeň není zobrazen, jako v \\u221A\\uD835\\uDC65

```cpp
virtual void Aspose::Slides::MathText::IMathRadical::set_HideDegree(bool value)=0
```

## Poznámky


Příklad: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // krychlový kořen
radical->set_HideDegree(true);
```

## Viz také

* Třída [IMathRadical](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)