---
title: "System::StringExtra"
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 911
url: /nl/system.stringextra/
---
## Functies

| Functie | Beschrijving |
| --- | --- |
| [String](../system/string/) [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<[String](../system/string/)\>\&) | Voegt een stringarray samen. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&) | Voegt strings samen. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Voegt strings samen. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Voegt strings samen. |
| std::enable_if_t\<[IsSmartPtr](../system/issmartptr/)\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Converteert meerdere objecten naar een string en voegt de resulterende strings samen. Specialisatie voor [SmartPtr](../system/smartptr/) types. |
| std::enable_if_t\<std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Converteert meerdere objecten naar een string en voegt de resulterende strings samen. Specialisatie voor aritmetische types. |
| std::enable_if_t<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&\!std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Converteert meerdere objecten naar een string en voegt de resulterende strings samen. Specialisatie voor structuren en andere waardetypen. |