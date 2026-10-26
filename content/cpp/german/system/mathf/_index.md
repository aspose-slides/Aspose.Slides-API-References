---
title: MathF
second_title: Aspose.Slides für C++ API-Referenz
description: Enthält mathematische Funktionen für Gleitkommawerte mit einfacher Genauigkeit. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen.
type: docs
weight: 1795
url: /de/system/mathf/
---
## MathF Struktur

Enthält mathematische Funktionen für Gleitkommawerte mit einfacher Genauigkeit. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen.

```cpp
class MathF
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static T [Abs](./abs/)(T) | Gibt den Absolutwert des angegebenen Werts zurück. |
| static **float** [Acos](./acos/)(**float**) | Berechnet den Arcus-Cosinus des angegebenen Werts. |
| static **float** [Asin](./asin/)(**float**) | Berechnet den Arcus-Sinus des angegebenen Werts. |
| static **float** [Atan](./atan/)(**float**) | Berechnet den Arcus-Tangens des angegebenen Werts. |
| static **float** [Atan2](./atan2/)(**float**, **float**) | Berechnet den Arcus-Tangens des Verhältnisses der angegebenen Werte. |
| static **float** [Ceiling](./ceiling/)(**float**) | Gibt den kleinsten ganzzahligen Wert zurück, der größer oder gleich dem angegebenen Wert ist. |
| static **float** [Cos](./cos/)(**float**) | Berechnet den Kosinus des angegebenen Werts. |
| static **float** [Cosh](./cosh/)(**float**) | Berechnet den hyperbolischen Kosinus des angegebenen Werts. |
| static **float** [Exp](./exp/)(**float**) | Gibt die e-Konstante hoch die angegebene Potenz zurück. |
| static **float** [Floor](./floor/)(**float**) | Gibt den größten ganzzahligen Wert zurück, der kleiner oder gleich dem angegebenen Wert ist. |
| static **float** [IEEERemainder](./ieeeremainder/)(**float**, **float**) | Gibt den Rest der Division einer angegebenen Zahl durch eine andere angegebene Zahl zurück. |
| static **float** [Log](./log/)(**float**) | Gibt den natürlichen Logarithmus des angegebenen Werts zurück. |
| static **float** [Log](./log/)(**float**, **float**) | Gibt den Logarithmus des angegebenen Werts zur angegebenen Basis zurück. |
| static **float** [Log10](./log10/)(**float**) | Gibt den Logarithmus zur Basis 10 des angegebenen Werts zurück. |
| static **float** [Pow](./pow/)(**float**, **float**) | Gibt den angegebenen Wert hoch die angegebene Potenz zurück. |
| static **float** [Round](./round/)(**float**) | Rundet den angegebenen Wert auf den nächsten ganzzahligen Wert. |
| static **float** [Round](./round/)(**float**, int) | Rundet den angegebenen Wert auf den nächsten Wert mit der angegebenen Anzahl an Nachkommastellen. |
| static **float** [Round](./round/)(**float**, [MidpointRounding](../midpointrounding/)) | Rundet den angegebenen Wert auf die nächste ganze Zahl. Ein Parameter gibt das Verhalten der Funktion an, wenn der angegebene Wert gleich weit von zwei nächsten Zahlen entfernt ist. |
| static **float** [Round](./round/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Rundet den angegebenen Wert auf den nächsten Wert mit der angegebenen Anzahl an Nachkommastellen. Ein Parameter gibt das Verhalten der Funktion an, wenn der angegebene Wert gleich weit von zwei nächsten Zahlen entfernt ist. |
| static **float** [RoundImpl](./roundimpl/)(**float**, int, [MidpointRounding](../midpointrounding/)) | Rundet den angegebenen Wert auf den nächsten Wert mit der angegebenen Anzahl an Nachkommastellen. Ein Parameter gibt das Verhalten der Funktion an, wenn der angegebene Wert gleich weit von zwei nächsten Zahlen entfernt ist. |
| static std::enable_if\<std::is_integral\<T\>::value\&&\!std::is_unsigned\<T\>::value, int\>::type [Sign](./sign/)(T) | Bestimmt das Vorzeichen des angegebenen vorzeichenbehafteten ganzzahligen Werts. |
| static std::enable_if\<std::is_floating_point\<T\>::value, int\>::type [Sign](./sign/)(T) | Bestimmt das Vorzeichen des angegebenen Gleitkommawerts. |
| static **float** [Sin](./sin/)(**float**) | Berechnet den Sinus des angegebenen Werts. |
| static **float** [Sinh](./sinh/)(**float**) | Berechnet den hyperbolischen Sinus des angegebenen Werts. |
| static **float** [Sqrt](./sqrt/)(**float**) | Gibt die Quadratwurzel des angegebenen Werts zurück. |
| static **float** [Tan](./tan/)(**float**) | Berechnet den Tangens des angegebenen Werts. |
| static **float** [Tanh](./tanh/)(**float**) | Berechnet den hyperbolischen Tangens des angegebenen Werts. |
| static **float** [Truncate](./truncate/)(**float**) | Gibt einen Gleitkommawert zurück, dessen ganzzahliger Teil dem des angegebenen Werts entspricht, wobei alle Nachkommastellen verworfen werden. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static [E](./e/) | Basis des natürlichen Logarithmus. |
| static constexpr [MaxRoundingDigits](./maxroundingdigits/) |  |
| static [PI](./pi/) | Die Zahl Pi-Konstante. |
| static [Tau](./tau/) | Tau-Wert. |
## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)