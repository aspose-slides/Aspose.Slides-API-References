---
title: ReadOnlySpan
second_title: Aspose.Slides für C++ API Referenz
description: Weiterleitung zur Verwendung innerhalb der Span-Klasse.
type: docs
weight: 1210
url: /de/system/readonlyspan/
---
## ReadOnlySpan Klasse

Vorwärts zur Verwendung innerhalb der Klasse [Span](../span/).

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span. Diese Klasse bietet eine typensichere Möglichkeit, mit zusammenhängenden Sequenzen von Objekten in schreibgeschützter Weise zu arbeiten. Sie kann verwendet werden, um Arrays, Stack-Arrays oder rohe Zeiger zu umschließen, während die Grenzüberprüfung beibehalten wird. Der [ReadOnlySpan](./) besitzt den Speicher, auf den er zeigt, nicht – er ist lediglich eine Ansicht auf bestehenden Speicher. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  [ReadOnlySpan](./readonlyspan/)(const [Span](../span/)\<T\>\&) | Konstruiert einen schreibgeschützten Span aus einem regulären Span. |
| static [ThisType](./) [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | Konvertiert ein Array in ein [ReadOnlySpan](./). |

## Bemerkungen

Stellt einen schreibgeschützten zusammenhängenden Bereich beliebigen Speichers dar.

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)