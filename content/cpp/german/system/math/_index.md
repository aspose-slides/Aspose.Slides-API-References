---
title: Math
second_title: Aspose.Slides für C++ API-Referenz
description: Enthält mathematische Funktionen. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals auf irgendeine Weise Instanzen davon erstellen.
type: docs
weight: 1782
url: /de/system/math/
---
## Math-Struktur

Enthält mathematische Funktionen. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals auf irgendeine Weise Instanzen davon erstellen.

```cpp
class Math
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static T [Abs](./abs/)(T) | Gibt den absoluten Wert des angegebenen Werts zurück. |
| static [Decimal](../decimal/) [Abs](./abs/)(const [Decimal](../decimal/)\&) | Gibt den absoluten Wert eines von dem angegebenen [Decimal](../decimal/)-Objekt dargestellten Wertes zurück. |
| static **double** [Acos](./acos/)(**double**) | Berechnet den Arkuskosinus des angegebenen Werts. |
| static **double** [Asin](./asin/)(**double**) | Berechnet den Arkussinus des angegebenen Werts. |
| static **double** [Atan](./atan/)(**double**) | Berechnet den Arkustangens des angegebenen Werts. |
| static **double** [Atan2](./atan2/)(**double**, **double**) | Berechnet den Arkustangens des Verhältnisses der angegebenen Werte. |
| static **int64_t** [BigMul](./bigmul/)(int, int) | Gibt das vollständige Produkt zweier 32-Bit-Ganzzahlen zurück. |
| static [Decimal](../decimal/) [Ceiling](./ceiling/)(const [Decimal](../decimal/)\&) | Gibt den kleinsten ganzzahligen Wert zurück, der größer oder gleich dem angegebenen Wert ist. |
| static **double** [Ceiling](./ceiling/)(**double**) | Gibt den kleinsten ganzzahligen Wert zurück, der größer oder gleich dem angegebenen Wert ist. |
| static **double** [Cos](./cos/)(**double**) | Berechnet den Kosinus des angegebenen Werts. |
| static **double** [Cosh](./cosh/)(**double**) | Berechnet den hyperbolischen Kosinus des angegebenen Werts. |
| static int [DivRem](./divrem/)(int, int, int\&) | Berechnet den Quotienten zweier 32-Bit-Ganzzahlen und den Rest. |
| static **int64_t** [DivRem](./divrem/)(**int64_t**, **int64_t**, **int64_t**\&) | Berechnet den Quotienten zweier 64-Bit-Ganzzahlen und den Rest. |
| static **double** [Exp](./exp/)(**double**) | Gibt die e-Konstante zur angegebenen Potenz zurück. |
| static [Decimal](../decimal/) [Floor](./floor/)(const [Decimal](../decimal/)\&) | Gibt den größten ganzzahligen Wert zurück, der kleiner oder gleich dem angegebenen Wert ist. |
| static **double** [Floor](./floor/)(**double**) | Gibt den größten ganzzahligen Wert zurück, der kleiner oder gleich dem angegebenen Wert ist. |
| static **double** [IEEERemainder](./ieeeremainder/)(**double**, **double**) | Gibt den Rest zurück, der bei der Division einer angegebenen Zahl durch eine andere angegebene Zahl entsteht. |
| static **double** [Log](./log/)(**double**) | Gibt den natürlichen Logarithmus des angegebenen Werts zurück. |
| static **double** [Log](./log/)(**double**, **double**) | Gibt den Logarithmus des angegebenen Werts zur angegebenen Basis zurück. |
| static **double** [Log10](./log10/)(**double**) | Gibt den Logarithmus zur Basis 10 des angegebenen Werts zurück. |
| static auto [Max](./max/)(T0, T1) | Gibt den größten Wert der beiden angegebenen numerischen Werte zurück. |
| static T0 [Max](./max/)(T0, T1) | Gibt den größten Wert der beiden angegebenen numerischen Werte zurück. |
| **float** [Max_](./max_/)(**float**, **float**) | Gibt den größten Gleitkommawert einfacher Genauigkeit der beiden angegebenen zurück. |
| **double** [Max_](./max_/)(**double**, **double**) | Gibt den größten Gleitkommawert doppelter Genauigkeit der beiden angegebenen zurück. |
| static auto [Min](./min/)(T0, T1) | Gibt den kleinsten Wert der beiden angegebenen numerischen Werte zurück. |
| static T0 [Min](./min/)(T0, T1) | Gibt den kleinsten Wert der beiden angegebenen numerischen Werte zurück. |
| **float** [Min_](./min_/)(**float**, **float**) | Gibt den kleinsten Gleitkommawert einfacher Genauigkeit der beiden angegebenen zurück. |
| **double** [Min_](./min_/)(**double**, **double**) | Gibt den kleinsten Gleitkommawert doppelter Genauigkeit der beiden angegebenen zurück. |
| static T [Modulus](./modulus/)(T, T) | Berechnet den Rest, der bei der Division eines angegebenen Werts durch einen anderen angegebenen Wert entsteht. |
| static **double** [Pow](./pow/)(**double**, **double**) | Gibt den angegebenen Wert zur angegebenen Potenz zurück. |
| static **double** [Round](./round/)(**double**) | Rundet den angegebenen Wert auf den nächsten ganzzahligen Wert. |
| static **double** [Round](./round/)(**double**, int) | Rundet den angegebenen Wert auf den nächsten Wert mit der angegebenen Anzahl von Dezimalstellen. |
| static **double** [Round](./round/)(**double**, [MidpointRounding](../midpointrounding/)) | Rundet den angegebenen Wert auf die nächste ganze Zahl. Ein Parameter gibt das Verhalten der Funktion an, wenn der angegebene Wert gleich weit von zwei nächsten Zahlen entfernt ist. |
| static **double** [Round](./round/)(**double**, int, [MidpointRounding](../midpointrounding/)) | Rundet den angegebenen Wert auf den nächsten Wert mit der angegebenen Anzahl von Dezimalstellen. Ein Parameter gibt das Verhalten der Funktion an, wenn der angegebene Wert gleich weit von zwei nächsten Zahlen entfernt ist. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&) | Rundet den angegebenen Wert auf den nächsten ganzzahligen Wert. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int) | Rundet den angegebenen Wert auf den nächsten Wert mit der angegebenen Anzahl von Dezimalstellen. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, [MidpointRounding](../midpointrounding/)) | Rundet den angegebenen Wert auf die nächste ganze Zahl. Ein Parameter gibt das Verhalten der Funktion an, wenn der angegebene Wert gleich weit von zwei nächsten Zahlen entfernt ist. |
| static [Decimal](../decimal/) [Round](./round/)(const [Decimal](../decimal/)\&, int, [MidpointRounding](../midpointrounding/)) | Rundet den angegebenen Wert auf den nächsten Wert mit der angegebenen Anzahl von Dezimalstellen. Ein Parameter gibt das Verhalten der Funktion an, wenn der angegebene Wert gleich weit von zwei nächsten Zahlen entfernt ist. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Bestimmt das Vorzeichen des angegebenen vorzeichenbehafteten ganzzahligen Werts. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Bestimmt das Vorzeichen des angegebenen Gleitkommawertes. |
| static int [Sign](./sign/)(const [Decimal](../decimal/)\&) | Bestimmt das Vorzeichen des angegebenen Dezimalwertes. |
| static **double** [Sin](./sin/)(**double**) | Berechnet den Sinus des angegebenen Werts. |
| static **double** [Sinh](./sinh/)(**double**) | Berechnet den hyperbolischen Sinus des angegebenen Werts. |
| static **double** [Sqrt](./sqrt/)(**double**) | Gibt die Quadratwurzel des angegebenen Werts zurück. |
| static **double** [Tan](./tan/)(**double**) | Berechnet den Tangens des angegebenen Werts. |
| static **double** [Tanh](./tanh/)(**double**) | Berechnet den hyperbolischen Tangens des angegebenen Werts. |
| static [Decimal](../decimal/) [Truncate](./truncate/)(const [Decimal](../decimal/)\&) | Gibt das [Decimal](../decimal/)-Objekt zurück, das einen Wert repräsentiert, dessen ganzzahliger Teil dem des von dem angegebenen [Decimal](../decimal/)-Objekt dargestellten Werts entspricht, wobei alle Nachkommastellen verworfen werden. |
| static **double** [Truncate](./truncate/)(**double**) | Gibt einen double-Genauigkeits-Gleitkommawert zurück, dessen ganzzahliger Teil dem des angegebenen Werts entspricht, wobei alle Nachkommastellen verworfen werden. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static [E](./e/) | Basis des natürlichen Logarithmus. |
| static [NaN](./nan/) | Stellt einen "not-a-number"-Wert dar. |
| static [NegativeInfinity](./negativeinfinity/) | Stellt die negative Unendlichkeit dar. |
| static [PI](./pi/) | Die Kreiszahl Pi-Konstante. |
| static [PositiveInfinity](./positiveinfinity/) | Stellt die positive Unendlichkeit dar. |

## Anmerkungen



```cpp
#include "system/math.h"
#include <iostream>

int main()
{
  using namespace System;

  // Gibt die absoluten Werte aus.
  for (int i = -1; i < 2; ++i)
  {
    std::cout << Math::Abs(i) << " ";
  }
  std::cout << std::endl;

  // Gibt den Sinus von PI/2 und den Kosinus von PI aus.
  std::cout << "sin(PI/2)=" << Math::Sin(Math::PI/2) << "; cos(PI)=" << Math::Cos(Math::PI) << std::endl;

  return 0;
}
/*
Dieses Codebeispiel erzeugt die folgende Ausgabe:
1 0 1
sin(PI/2)=1; cos(PI)=-1
*/
```

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)