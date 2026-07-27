---
title: "System::TestPredicates::TypeTraits"
second_title: "Referencia de la API de Aspose.Slides para C++"
description: 
type: docs
weight: 963
url: /es/system.testpredicates.typetraits/
---
## Estructuras

| Estructura | Descripción |
| --- | --- |
| [has_data_method](./has_data_method/) | Comprueba si un tipo tiene el método data(). Si lo tiene, hereda std::true_type; de lo contrario, hereda std::false_type. |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | Especialización para el tipo BitArray que proporciona un tipo boost que es inaccesible allí. |
| [has_print_to_method](./has_print_to_method/) | Comprueba la sobrecarga de la función PrintTo que acepta el tipo dado como primer argumento. Si existe una sobrecarga, hereda std::true_type; de lo contrario, hereda std::false_type. |
| [IsCppContainer](./iscppcontainer/) | Comprueba si un tipo específico es un contenedor al estilo STL. Para ello, verifica la existencia de los tipos miembro iterator y const_iterator. Si ambos existen, hereda std::true_type; de lo contrario, hereda std::false_type. |
| [IsEnumerable](./isenumerable/) | Comprueba si el tipo tiene la especialización [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/) como tipo base. Si es así, el miembro value se establece en true; de lo contrario se establece en false. |
| [LargestFPType](./largestfptype/) | Proporciona un alias para el tipo de punto flotante más largo disponible. Ignora los tipos que no son de punto flotante. |

## Definiciones de tipo

| Alias de tipo | Descripción |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | Comprueba que **T1** sea aritmético y **T2** sea de punto flotante, o viceversa. Si es así, establece el miembro value en true; de lo contrario es false. |
| [AnyOfDecimal](./anyofdecimal/) | Comprueba que al menos uno de los argumentos de tipo sea [System::Decimal](../system/decimal/). Si es así, establece el miembro value en true; de lo contrario es false. |
| [IsArray](./isarray/) | Comprueba si el tipo es una especialización [System::Array](../system/array/). Si es así, el miembro value se establece en true; de lo contrario se establece en false. |
| [IsList](./islist/) | Comprueba si el tipo es una especialización [System::Collections::Generic::List](../system.collections.generic/list/). Si es así, el miembro value se establece en true; de lo contrario se establece en false. |
| [BothArrayOrList](./botharrayorlist/) | Comprueba si ambos argumentos de tipo son matrices o listas. Si es así, el miembro value se establece en true; de lo contrario se establece en false. |
| [BothEnumerable](./bothenumerable/) | Comprueba si ambos argumentos de tipo son IEnumerable. Si es así, el miembro value se establece en true; de lo contrario se establece en false. |