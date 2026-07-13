---
title: IBlur
second_title: Aspose.Slides dla Androida poprzez dokumentację API Java
description: Reprezentuje efekt rozmycia, który jest stosowany do całego kształtu, włącznie z jego wypełnieniem.
type: docs
url: /pl/com.aspose.slides/iblur/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Reprezentuje efekt rozmycia, który jest stosowany do całego kształtu, włącznie z jego wypełnieniem. Wszystkie kanały kolorów, włącznie z alfą, są dotknięte.
## Metody

| Metoda | Opis |
| --- | --- |
| [getRadius()](#getRadius--) | Zwraca lub ustawia promień rozmycia. |
| [setRadius(double value)](#setRadius-double-) | Zwraca lub ustawia promień rozmycia. |
| [getGrow()](#getGrow--) | Określa, czy granice obiektu powinny zostać powiększone w wyniku rozmycia. |
| [setGrow(boolean value)](#setGrow-boolean-) | Określa, czy granice obiektu powinny zostać powiększone w wyniku rozmycia. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Zwraca lub ustawia promień rozmycia. Odczyt/zapis double.

**Zwraca:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Zwraca lub ustawia promień rozmycia. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Określa, czy granice obiektu powinny zostać powiększone w wyniku rozmycia. True wskazuje, że granice są powiększane, natomiast false wskazuje, że nie są. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

Określa, czy granice obiektu powinny zostać powiększone w wyniku rozmycia. True wskazuje, że granice są powiększane, natomiast false wskazuje, że nie są. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |