---
title: IBlurEffectiveData
second_title: Aspose.Slides dla Androida poprzez odniesienie API Java
description: Niezmienny obiekt reprezentujący efekt Blur, który jest stosowany do całego kształtu, włącznie z jego wypełnieniem.
type: docs
url: /pl/com.aspose.slides/iblureffectivedata/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Niezmienny obiekt reprezentujący efekt Blur, który jest stosowany do całego kształtu, włącznie z jego wypełnieniem. Wszystkie kanały kolorów, w tym alfa, są pod wpływem.
## Metody

| Metoda | Opis |
| --- | --- |
| [getRadius()](#getRadius--) | Zwraca lub ustawia promień rozmycia. Tylko do odczytu double. |
| [getGrow()](#getGrow--) | Określa, czy granice obiektu powinny zostać powiększone w wyniku rozmycia. |

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

Określa, czy granice obiektu powinny zostać powiększone w wyniku rozmycia. True wskazuje, że granice są powiększane, natomiast false wskazuje, że nie są. Tylko do odczytu boolean.

**Zwraca:**
boolean