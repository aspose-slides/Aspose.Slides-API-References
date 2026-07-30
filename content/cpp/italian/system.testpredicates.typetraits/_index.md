---
title: "System::TestPredicates::TypeTraits"
second_title: Riferimento API Aspose.Slides per C++
description: 
type: docs
weight: 963
url: /it/system.testpredicates.typetraits/
---
## Strutture

| Struttura | Descrizione |
| --- | --- |
| [has_data_method](./has_data_method/) | Verifica se un tipo ha il metodo data(). Se lo ha, eredita std::true_type, altrimenti eredita std::false_type. |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | Specializzazione per il tipo BitArray che fornisce il tipo boost, che è inaccessibile lì. |
| [has_print_to_method](./has_print_to_method/) | Verifica la presenza di una sovraccarico della funzione PrintTo che accetta il tipo fornito come primo argomento. Se esiste un overload, eredita std::true_type, altrimenti eredita std::false_type. |
| [IsCppContainer](./iscppcontainer/) | Verifica se un tipo specifico è un contenitore di stile STL. Per farlo, verifica l'esistenza dei tipi membro iterator e const_iterator. Se entrambi esistono, eredita std::true_type, altrimenti eredita std::false_type. |
| [IsEnumerable](./isenumerable/) | Verifica se il tipo ha la specializzazione [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/) come tipo base. In tal caso, il membro value è impostato a true, altrimenti è impostato a false. |
| [LargestFPType](./largestfptype/) | Fornisce un alias per il tipo a virgola mobile più lungo fornito. Ignora i tipi non a virgola mobile. |

## Definizioni di tipo

| Typedef | Descrizione |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | Verifica che **T1** sia aritmetico e **T2** sia a virgola mobile, oppure viceversa. In tal caso, imposta il membro value a true, altrimenti è false. |
| [AnyOfDecimal](./anyofdecimal/) | Verifica che almeno uno degli argomenti di tipo sia [System::Decimal](../system/decimal/). In tal caso, imposta il membro value a true, altrimenti è false. |
| [IsArray](./isarray/) | Verifica se il tipo è una specializzazione [System::Array](../system/array/). In tal caso, il membro value è impostato a true, altrimenti è impostato a false. |
| [IsList](./islist/) | Verifica se il tipo è una specializzazione [System::Collections::Generic::List](../system.collections.generic/list/). In tal caso, il membro value è impostato a true, altrimenti è impostato a false. |
| [BothArrayOrList](./botharrayorlist/) | Verifica se entrambi gli argomenti di tipo sono array o liste. In tal caso, il membro value è impostato a true, altrimenti è impostato a false. |
| [BothEnumerable](./bothenumerable/) | Verifica se entrambi gli argomenti di tipo sono IEnumerable. In tal caso, il membro value è impostato a true, altrimenti è impostato a false. |