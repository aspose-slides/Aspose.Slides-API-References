---
title: "System::StringExtra"
second_title: Aspose.Slides pro C++ API Reference
description: 
type: docs
weight: 911
url: /cs/system.stringextra/
---
## Funkce

| Funkce | Popis |
| --- | --- |
| [String](../system/string/) [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<[String](../system/string/)\>\&) | Spojuje pole řetězců. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&) | Spojuje řetězce. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Spojuje řetězce. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Spojuje řetězce. |
| std::enable_if_t\<[IsSmartPtr](../system/issmartptr/)\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Převádí více objektů na řetězec a spojuje výsledné řetězce. Specializace pro typy [SmartPtr](../system/smartptr/). |
| std::enable_if_t\<std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Převádí více objektů na řetězec a spojuje výsledné řetězce. Specializace pro aritmetické typy. |
| std::enable_if_t<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&\!std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Převádí více objektů na řetězec a spojuje výsledné řetězce. Specializace pro struktury a další typy hodnot. |