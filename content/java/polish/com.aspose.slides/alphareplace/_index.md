---
title: AlphaReplace
second_title: Aspose.Slides dla Java – dokumentacja API
description: Reprezentuje efekt Alpha Replace.
type: docs
url: /pl/com.aspose.slides/alphareplace/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IAlphaReplace](../../com.aspose.slides/ialphareplace), com.aspose.slides.IVisualEffect
```
public final class AlphaReplace extends ImageTransformOperation implements IAlphaReplace, IVisualEffect
```

Reprezentuje efekt Alpha Replace. Wartości alfa (przezroczystości) efektu są zastępowane stałą wartością alfa.
## Metody

| Metoda | Opis |
| --- | --- |
| [getEffective()](#getEffective--) | Pobiera skuteczne dane efektu Alpha Replace z uwzględnionym dziedziczeniem. |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy określony [AlphaReplace](../../com.aspose.slides/alphareplace) jest równy bieżącemu [AlphaReplace](../../com.aspose.slides/alphareplace). |
| [hashCode()](#hashCode--) | Służy jako funkcja mieszająca dla określonego typu. |
### getEffective() {#getEffective--}
```
public final IAlphaReplaceEffectiveData getEffective()
```


Pobiera skuteczne dane efektu Alpha Replace z uwzględnionym dziedziczeniem.

**Zwraca:**
[IAlphaReplaceEffectiveData](../../com.aspose.slides/ialphareplaceeffectivedata) - Obiekt [IAlphaReplaceEffectiveData](../../com.aspose.slides/ialphareplaceeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Określa, czy określony [AlphaReplace](../../com.aspose.slides/alphareplace) jest równy bieżącemu [AlphaReplace](../../com.aspose.slides/alphareplace).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaReplace](../../com.aspose.slides/alphareplace) do porównania. |

**Zwraca:**
boolean - prawda, jeśli obiekty są równe; w przeciwnym razie fałsz.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Służy jako funkcja mieszająca dla określonego typu.

**Zwraca:**
int - Kod mieszający dla bieżącego obiektu.