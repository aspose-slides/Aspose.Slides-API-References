---
title: MakeSharedPtr()
second_title: Aspose.Slides voor C++ API Referentie
description: Converteert een ruwe pointer naar een slimme pointer.
type: docs
weight: 2900
url: /nl/system/makesharedptr/
---
## System::MakeSharedPtr(X *) functie


Zet ruwe pointer om naar een slimme pointer.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(X *p)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| X | Pointee-type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| p | X * | Ruwe pointer naar object. |

### Retourwaarde

Gedeelde slimme pointer naar object.

## System::MakeSharedPtr(const X *) functie


Zet ruwe pointer om naar een slimme pointer. Overload voor const-pointers. Handig bijv. bij het gebruik van de variabele 'this' in C#-methoden die naar const worden vertaald.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(const X *p)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| X | Pointee-type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| p | const X * | Ruwe pointer naar object. |

### Retourwaarde

Gedeelde slimme pointer naar object.

## Zie ook

* Klasse [SmartPtr](../smartptr/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)