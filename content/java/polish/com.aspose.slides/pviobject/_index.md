---
title: PVIObject
second_title: Aspose.Slides dla Java – dokumentacja API
description: Zapewnia podstawową infrastrukturę serwisową dla obiektów, które mogą być przedmiotem dziedziczenia wartości własności.
type: docs
url: /pl/com.aspose.slides/pviobject/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

Umożliwia podstawową infrastrukturę serwisową dla obiektów, które mogą być przedmiotem dziedziczenia wartości własności.
## Metody

| Metoda | Opis |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Porównuje z określonym obiektem. |
| [hashCode()](#hashCode--) | Zwraca kod skrótu. |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```


Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public long getVersion()
```


Wersja. Tylko do odczytu long.

**Zwraca:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```


Zwraca rodzica IPresentationComponent. Tylko do odczytu [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Zwraca:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```




**Zwraca:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)
### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```


Zwraca bazowy slajd. Tylko do odczytu [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Zwraca:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```


Zwraca prezentację. Tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**
[Presentation](../../com.aspose.slides/presentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Porównuje z określonym obiektem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | Obiekt do porównania. |

**Zwraca:**
boolean - True jeśli obiekty są równe, w przeciwnym razie false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Zwraca kod skrótu.

**Zwraca:**
int - Kod skrótu.