---
title: Span
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt einen zusammenhängenden Bereich beliebigen Speichers dar, ähnlich wie std::span von C++20."
type: docs
weight: 1262
url: /de/system/span/
---
## Span Klasse


Stellt einen zusammenhängenden Bereich beliebigen Speichers dar, ähnlich wie C++20's std::span.

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span. Diese Klasse bietet eine typsichere Möglichkeit, mit zusammenhängenden Sequenzen von Objekten zu arbeiten. Sie kann verwendet werden, um Arrays, Stack-Arrays oder rohe Zeiger zu umschließen, während die Bereichsprüfung erhalten bleibt. Der [Span](./) besitzt den Speicher, auf den er zeigt, nicht – er ist lediglich eine Ansicht auf vorhandenen Speicher. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [Clear](./clear/)() const | Löscht den Inhalt des Spans, indem alle Elemente auf den Standardwert gesetzt werden. |
| void [Fill](./fill/)(const T\&) const | Füllt den Span mit dem angegebenen Wert. |
| static [ThisType](./) [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | Konvertiert ein Array in ein [Span](./). |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)