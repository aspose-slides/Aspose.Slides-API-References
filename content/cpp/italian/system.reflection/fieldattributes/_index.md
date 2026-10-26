---
title: FieldAttributes
second_title: Riferimento API Aspose.Slides per C++
description: Attributi del campo riflessi.
type: docs
weight: 170
url: /it/system.reflection/fieldattributes/
---
## FieldAttributes enum

Attributi del campo riflessi.

```cpp
enum class FieldAttributes
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| FieldAccessMask | 7 | Maschera di accesso del membro. Usa questa maschera per recuperare le informazioni di accessibilità. |
| PrivateScope | 0 | Membri non referenziabili. |
| Private | 1 | Membri privati. |
| FamANDAssem | 2 | Membri privati e a livello di assembly. |
| Assembly | 3 | Membri a livello di assembly. |
| Family | 4 | Membri accessibili dal tipo e dai sottotipi. |
| FamORAssem | 5 | Membri accessibili dal tipo, dai sottotipi e dall'assembly. |
| Public | 6 | Membri accessibili a chiunque. |
| Static | 16 | Membri statici in contrapposizione ai membri di istanza. |
| InitOnly | 32 | Membri costanti che possono solo essere inizializzati ma non modificati. |
| Literal | 64 | Membri costanti a tempo di compilazione. |
| NotSerialized | 128 | Membri non serializzati. |
| SpecialName | 512 | Campo speciale con uno dei nomi seguenti. |
| PinvokeImpl | 8192 | Implementazione interop inoltrata. |
| ReservedMask | 38144 | Flag riservati solo per l'uso a runtime. |
| RTSpecialName | 1024 | Il runtime dovrebbe verificare la codifica del nome. |
| HasFieldMarshal | 4096 | È presente l'informazione di marshalling. |
| HasDefault | 32768 | È presente il valore predefinito. |
| HasFieldRVA | 256 | È presente l'RVA. |

## Vedi anche

* Namespace [System::Reflection](../)
* Libreria [Aspose.Slides](../../)