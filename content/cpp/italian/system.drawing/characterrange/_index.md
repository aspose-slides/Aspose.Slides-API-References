---
title: CharacterRange
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un intervallo di posizioni di caratteri in una stringa. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe System::SmartPtr per gestire gli oggetti di questo tipo."
type: docs
weight: 40
url: /it/system.drawing/characterrange/
---
## CharacterRange classe


Rappresenta un intervallo di posizioni dei caratteri in una stringa. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Never use [System::SmartPtr](../../system/smartptr/) classe per gestire oggetti di questo tipo.

```cpp
class CharacterRange
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [CharacterRange](./characterrange/)(**int32_t**, **int32_t**) | Crea una nuova istanza della classe [CharacterRange](./) che rappresenta l'intervallo specificato. |
|  [CharacterRange](./characterrange/)() | Crea una nuova istanza della classe [CharacterRange](./) che rappresenta un intervallo vuoto. |
| **int32_t** [get_First](./get_first/)() const | Restituisce la posizione del primo carattere dell'intervallo rappresentato dall'oggetto corrente. |
| **int32_t** [get_Length](./get_length/)() const | Restituisce il numero di caratteri dell'intervallo rappresentato dall'oggetto corrente. |
| **bool** [operator!=](./operator_not_equal/)(const [CharacterRange](./)\&) const | Determina se l'oggetto corrente e quello specificato rappresentano intervalli distinti. |
| **bool** [operator==](./operator_equal_equal/)(const [CharacterRange](./)\&) const | Determina se l'oggetto corrente e quello specificato rappresentano lo stesso intervallo. |
| void [set_First](./set_first/)(**int32_t**) | Imposta la posizione del primo carattere dell'intervallo rappresentato dall'oggetto corrente. |
| void [set_Length](./set_length/)(**int32_t**) | Restituisce il numero di caratteri dell'intervallo rappresentato dall'oggetto corrente. |
## Vedi anche

* Spazio dei nomi [System::Drawing](../)
* Libreria [Aspose.Slides](../../)