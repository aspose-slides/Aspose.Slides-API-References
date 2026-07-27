---
title: "System::StringExtra"
second_title: Referencia de la API de Aspose.Slides para C++
description: 
type: docs
weight: 911
url: /es/system.stringextra/
---
## Funciones

| Function | Description |
| --- | --- |
| [String](../system/string/) [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<[String](../system/string/)\>\&) | Concatena una matriz de cadenas. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&) | Concatena cadenas. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Concatena cadenas. |
| [String](../system/string/) [Concat](./concat/)(const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&, const [String](../system/string/)\&) | Concatena cadenas. |
| std::enable_if_t\<[IsSmartPtr](../system/issmartptr/)\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Convierte múltiples objetos a cadena y concatena las cadenas resultantes. Especialización para [SmartPtr](../system/smartptr/) types. |
| std::enable_if_t\<std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Convierte múltiples objetos a cadena y concatena las cadenas resultantes. Especialización para tipos aritméticos. |
| std::enable_if_t<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&\!std::is_arithmetic\<T\>::value, [String](../system/string/)\> [Concat](./concat/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&) | Convierte múltiples objetos a cadena y concatena las cadenas resultantes. Especialización para estructuras y otros tipos de valor. |