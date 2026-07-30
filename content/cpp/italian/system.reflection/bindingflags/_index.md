---
title: BindingFlags
second_title: Riferimento API Aspose.Slides per C++
description: Definisce i membri e le modalità di ricerca dei tipi e dei binding.
type: docs
weight: 157
url: /it/system.reflection/bindingflags/
---
## Enum BindingFlags

Definisce i membri e le modalità di ricerca dei tipi e dei binding.

```cpp
enum class BindingFlags
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Default | 0 | Nessuna opzione speciale. |
| IgnoreCase | 1 | Ignora la differenza tra maiuscole e minuscole del nome durante la ricerca dell'elemento. |
| DeclaredOnly | 2 | Cerca solo i membri dichiarati nel tipo e non nei tipi base. |
| Instance | 4 | Scorre i membri di istanza. |
| Static | 8 | Scorre i membri statici. |
| Public | 16 | Scorre i membri pubblici. |
| NonPublic | 32 | Scorre i membri non pubblici. |
| FlattenHierarchy | 64 | Scorre i membri statici pubblici e protetti del tipo base. |
| InvokeMethod | 256 | Invoca il metodo. |
| CreateInstance | 512 | Crea un'istanza del tipo riflesso. |
| GetField | 1024 | Ottiene il valore del campo. |
| SetField | 2048 | Imposta il valore del campo. |
| GetProperty | 4096 | Ottiene il valore della proprietà. |
| SetProperty | 8192 | Imposta il valore della proprietà. |
| PutDispProperty | 16384 | Imposta la proprietà COM. |
| PutRefDispProperty | 32768 | Imposta la proprietà di riferimento COM. |
| ExactBinding | 65536 | Il binding del tipo deve essere esatto, senza alcuna modifica del tipo. |
| SuppressChangeType | 131072 | Non supportato. |
| OptionalParamBinding | 262144 | Seleziona il sovraccarico in base al numero di argomenti. |
| IgnoreReturn | 16777216 | Ignora il valore di ritorno dell'interoperabilità COM. |

## Vedi anche

* Spazio dei nomi [System::Reflection](../)
* Libreria [Aspose.Slides](../../)