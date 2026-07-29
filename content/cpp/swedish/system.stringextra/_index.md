---
title: "System::StringExtra"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 911
url: /sv/system.stringextra/
---
## Funktioner

| Funktion | Beskrivning |
| --- | --- |
| [String](../system/string/) [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<[String](../system/string/)\>\&) | Konkatenar strängarray. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&) | Konkatenar strängar. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Konkatenar strängar. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Konkatenar strängar. |
| std::enable_if_t\<[IsSmartPtr](../system/issmartptr/)\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Konverterar flera objekt till sträng och konkatenar resulterande strängar. Specialisering för [SmartPtr](../system/smartptr/) typer. |
| std::enable_if_t\<std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Konverterar flera objekt till sträng och konkatenar resulterande strängar. Specialisering för aritmetiska typer. |
| std::enable_if_t<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&\!std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Konverterar flera objekt till sträng och konkatenar resulterande strängar. Specialisering för strukturer och andra värdetyper. |