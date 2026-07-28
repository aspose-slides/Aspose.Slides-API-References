---
title: ToBox()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Umieszcza ten element w niewidzialnym pudełku (grupowanie logiczne), które służy do grupowania składników równania lub innego fragmentu tekstu matematycznego. Pudełkowany obiekt może (na przykład) pełnić rolę emulatora operatora z punktem wyrównania lub bez niego, służyć jako punkt podziału linii lub być grupowany w taki sposób, aby nie dopuszczać do podziałów linii wewnątrz.
type: docs
weight: 274
url: /pl/aspose.slides.mathtext/imathelement/tobox/
---
## IMathElement::ToBox() metoda


Umieszcza ten element w niewidzialnym pudełku (grupowanie logiczne), które służy do grupowania składników równania lub innego fragmentu tekstu matematycznego. Pudełkowany obiekt może (na przykład) pełnić rolę emulatora operatora z punktem wyrównania lub bez niego, służyć jako punkt podziału linii lub być grupowany w taki sposób, aby nie zezwalać na podziały linii w jego wnętrzu.

```cpp
virtual System::SharedPtr<IMathBox> Aspose::Slides::MathText::IMathElement::ToBox()=0
```


### Wartość zwracana

Logiczne pudełko z umieszczonym wewnątrz tym elementem
## Uwagi



Przykład: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Zobacz też

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathBox](../../imathbox/)
* Klasa [IMathElement](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)