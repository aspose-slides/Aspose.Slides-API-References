---
title: "System::StringExtra"
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 911
url: /de/system.stringextra/
---
## Funktionen

| Funktion | Beschreibung |
| --- | --- |
| [String](../system/string/) [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<[String](../system/string/)\>\&) | Verkettet ein String-Array. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&) | Verkettet Zeichenketten. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Verkettet Zeichenketten. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Verkettet Zeichenketten. |
| std::enable_if_t\<[IsSmartPtr](../system/issmartptr/)\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Konvertiert mehrere Objekte in einen String und verkettet die resultierenden Zeichenketten. Spezialisierung für [SmartPtr](../system/smartptr/) Typen. |
| std::enable_if_t\<std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Konvertiert mehrere Objekte in einen String und verkettet die resultierenden Zeichenketten. Spezialisierung für arithmetische Typen. |
| std::enable_if_t<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&\!std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Konvertiert mehrere Objekte in einen String und verkettet die resultierenden Zeichenketten. Spezialisierung für Strukturen und andere Werttypen. |
