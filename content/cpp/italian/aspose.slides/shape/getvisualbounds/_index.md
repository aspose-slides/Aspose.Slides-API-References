---
title: GetVisualBounds()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce i limiti visuali della forma calcolati dal suo contenuto renderizzato.
type: docs
weight: 677
url: /it/aspose.slides/shape/getvisualbounds/
---
## Shape::GetVisualBounds() metodo


Restituisce i limiti visuali della forma calcolati dal suo contenuto renderizzato.

```cpp
System::Drawing::RectangleF Aspose::Slides::Shape::GetVisualBounds()
```


### Valore di ritorno

Un [System::Drawing::RectangleF](../../../system.drawing/rectanglef/) che rappresenta i limiti visuali della forma nelle coordinate della diapositiva.
## Osservazioni


Il rettangolo restituito rappresenta i limiti allineati agli assi di tutti i contenuti prodotti dalla forma durante il rendering nello spazio delle coordinate della diapositiva.

Questi limiti possono differire dai limiti del modello della forma ([Shape::X](../), [Shape::Y](../), [Shape::Width](../), [Shape::Height](../)) e possono contenere coordinate negative se il contenuto renderizzato si estende oltre l'origine della diapositiva.

I limiti visuali tengono conto degli aspetti legati al rendering, come le trasformazioni (ad esempio, rotazione), la larghezza e le giunzioni del tratto, il layout del testo e l'overflow, la geometria [SmartArt](../../../aspose.slides.smartart/), e altri effetti di layout che influenzano l'aspetto finale renderizzato della forma.

I limiti restituiti non sono ritagliati al rettangolo della diapositiva. 

## Vedi anche

* Classe [RectangleF](../../../system.drawing/rectanglef/)
* Classe [Shape](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)