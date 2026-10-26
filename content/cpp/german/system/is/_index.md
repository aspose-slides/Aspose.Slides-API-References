---
title: Is()
second_title: Aspose.Slides für C++ API-Referenz
description: Implementiert die Übersetzung des 'is'-Deklarationsmusters.
type: docs
weight: 2302
url: /de/system/is/
---
## System::Is(const ExpressionT\&, ResultT\&) Funktion

Implementiert die Übersetzung des 'is'-Deklarationsmusters.

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| PatternT | zu prüfender Typ. |
| ExpressionT | Typ des linken Ausdrucks. |
| ResultT | Typ des Ergebnisausdrucks. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | const ExpressionT\& | Ausdruck, der geprüft wird. |
| result | ResultT\& | Variable, in die der geprüfte Typ zugewiesen wird. |

### Rückgabewert

true, wenn die Typprüfung erfolgreich ist, sonst false.

## System::Is(const ExpressionT\&, const ConstantT\&) Funktion

Implementiert die Übersetzung des 'is'-Konstantenmusters.

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ExpressionT | Typ des linken Ausdrucks. |
| ConstantT | Typ des Konstantenausdrucks. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | const ExpressionT\& | Ausdruck, der geprüft wird. |
| constant | const ConstantT\& | Ausdruck, der mit dem linken verglichen wird. |

### Rückgabewert

true, wenn die Typprüfung erfolgreich ist, sonst false.

## System::Is(const E\&, const A\&) Funktion

Top-Level-Abgleichsfunktion. Wendet ein Muster auf einen Wert an.

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| A | Mustertyp (muss von Details::Pattern erben). |
| E | Typ des zu matchenden Wertes. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| e | const E\& | Wert, gegen den abgeglichen werden soll. |
| a | const A\& | Auf anzuwendendes Muster. |

### Rückgabewert

true, wenn das Muster zum Wert passt.

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)