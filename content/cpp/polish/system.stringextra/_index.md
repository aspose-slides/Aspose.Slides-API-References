---
title: "System::StringExtra"
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: 
type: docs
weight: 911
url: /pl/system.stringextra/
---
## Funkcje

| Funkcja | Opis |
| --- | --- |
| [String](../system/string/) [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<[String](../system/string/)\>\&) | Łączy tablicę ciągów znaków. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&) | Łączy ciągi znaków. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Łączy ciągi znaków. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Łączy ciągi znaków. |
| std::enable_if_t\<[IsSmartPtr](../system/issmartptr/)\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Konwertuje wiele obiektów na ciąg znaków i łączy uzyskane ciągi. Specjalizacja dla typów [SmartPtr](../system/smartptr/). |
| std::enable_if_t\<std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Konwertuje wiele obiektów na ciąg znaków i łączy uzyskane ciągi. Specjalizacja dla typów arytmetycznych. |
| std::enable_if_t<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&\!std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Konwertuje wiele obiektów na ciąg znaków i łączy uzyskane ciągi. Specjalizacja dla struktur i innych typów wartościowych. |