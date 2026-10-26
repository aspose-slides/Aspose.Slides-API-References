---
title: Guid
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un Identificatore Unico Globale. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare la classe System::SmartPtr per gestire oggetti di questo tipo."
type: docs
weight: 885
url: /it/system/guid/
---
## Guid classe


Rappresenta un Identificatore Unico Globale Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare la classe [System::SmartPtr](../smartptr/) per gestire oggetti di questo tipo.

```cpp
class Guid
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | Esegue il confronto aritmetico dei GUID rappresentati dall'oggetto corrente e da quello specificato. |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | Determina se i GUID rappresentati dall'oggetto corrente e da quello specificato sono uguali. |
| int [GetHashCode](./gethashcode/)() const | Restituisce un codice hash per l'oggetto corrente. |
|  [Guid](./guid/)() | Crea un oggetto che rappresenta un GUID costituito interamente da zeri. |
|  [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Crea un oggetto che rappresenta un GUID specificato come un array di valori interi senza segno a 8 bit. |
|  [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Crea un oggetto che rappresenta un GUID specificato come una vista di array di valori interi senza segno a 8 bit. |
|  [Guid](./guid/)(const [String](../string/)\&) | Crea un oggetto che rappresenta un GUID specificato come stringa. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Crea un'istanza della classe [Guid](./) dai componenti GUID specificati. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | Crea un'istanza della classe [Guid](./) dai componenti GUID specificati. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Crea un'istanza della classe [Guid](./) dai numeri interi senza segno e byte specificati. |
|  [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Crea un'istanza della classe [Guid](./) dai numeri interi senza segno e byte specificati. |
|  [Guid](./guid/)(const [Guid](./)\&) | Crea un oggetto che rappresenta lo stesso GUID dell'oggetto specificato. |
| static [Guid](./) [NewGuid](./newguid/)() | Genera un nuovo GUID e restituisce un oggetto [Guid](./) che lo rappresenta. |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | Determina se i GUID rappresentati dall'oggetto corrente e da quello specificato non sono uguali. |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | Assegna all'oggetto corrente il valore GUID rappresentato dall'oggetto [Guid](./) specificato. |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | Determina se i GUID rappresentati dall'oggetto corrente e da quello specificato sono uguali. |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | Converte la rappresentazione stringa specificata di un GUID in un oggetto [Guid](./) equivalente. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | Converte il GUID rappresentato dall'oggetto corrente in un array di byte. |
| [String](../string/) [ToString](./tostring/)() const | Converte il GUID rappresentato dall'oggetto corrente nella sua rappresentazione stringa. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Converte il GUID rappresentato dall'oggetto corrente nella sua rappresentazione stringa usando il formato stringa specificato. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Converte il GUID rappresentato dall'oggetto corrente nella sua rappresentazione stringa usando il formato stringa e la cultura specificati. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | Prova a convertire la stringa specificata in un oggetto [Guid](./). |
|  [~Guid](./~guid/)() | Distruttore. |

## Campi

| Campo | Descrizione |
| --- | --- |
| static [Empty](./empty/) | Rappresenta un GUID con valore 0. |

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)