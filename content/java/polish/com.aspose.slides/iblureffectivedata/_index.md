---
title: IBlurEffectiveData
second_title: Aspose.Slides dla Java – Dokumentacja API
description: Niezmienny obiekt, który reprezentuje efekt Blur stosowany do całego kształtu, włącznie z jego wypełnieniem.
type: docs
url: /pl/com.aspose.slides/iblureffectivedata/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Niezmienny obiekt, który reprezentuje efekt Blur stosowany do całego kształtu, włącznie z jego wypełnieniem. Wszystkie kanały kolorów, w tym alfa, są modyfikowane.
## Metody

| Metoda | Opis |
| --- | --- |
| [getRadius()](#getRadius--) | Zwraca lub ustawia promień rozmycia. |
| [getGrow()](#getGrow--) | Określa, czy granice obiektu powinny być powiększone w wyniku rozmycia. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Zwraca lub ustawia promień rozmycia. Tylko do odczytu double.

**Zwraca:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Określa, czy granice obiektu powinny być powiększone w wyniku rozmycia. True wskazuje, że granice są powiększane, natomiast false wskazuje, że nie są. Tylko do odczytu boolean.

**Zwraca:**
boolean