---
title: "System::StringExtra"
second_title: Riferimento API di Aspose.Slides per C++
description: 
type: docs
weight: 911
url: /it/system.stringextra/
---
## Funzioni

| Funzione | Descrizione |
| --- | --- |
| [String](../system/string/) [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<[String](../system/string/)\>\&) | Concatena l'array di stringhe. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&) | Concatena le stringhe. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Concatena le stringhe. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Concatena le stringhe. |
| std::enable_if_t\<[IsSmartPtr](../system/issmartptr/)\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Converte più oggetti in stringa e concatena le stringhe risultanti. Specializzazione per i tipi [SmartPtr](../system/smartptr/). |
| std::enable_if_t\<std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Converte più oggetti in stringa e concatena le stringhe risultanti. Specializzazione per i tipi aritmetici. |
| std::enable_if_t<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&\!std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Converte più oggetti in stringa e concatena le stringhe risultanti. Specializzazione per le strutture e altri tipi di valore. |