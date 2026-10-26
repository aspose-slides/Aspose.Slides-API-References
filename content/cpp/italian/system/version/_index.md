---
title: Version
second_title: Riferimento API Aspose.Slides per C++
description: "Rappresenta un numero di versione. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe System::SmartPtr per gestire oggetti di questo tipo."
type: docs
weight: 1470
url: /it/system/version/
---
## Classe Versione

Rappresenta un numero di versione. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare la classe [System::SmartPtr](../smartptr/) per gestire oggetti di questo tipo.

```cpp
class Version
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| int [CompareTo](./compareto/)(const [Version](./)\&) const | Confronta le versioni rappresentate dall'oggetto corrente e dall'oggetto specificato. |
| **bool** [Equals](./equals/)(const [Version](./)\&) const | Determina se i numeri di versione rappresentati dagli oggetti corrente e specificato sono uguali. |
| int [get_Build](./get_build/)() const | Restituisce il numero di build. |
| int [get_Major](./get_major/)() const | Restituisce la versione principale. |
| **int16_t** [get_MajorRevision](./get_majorrevision/)() const | Restituisce il valore a 16 bit alto del numero di revisione. |
| int [get_Minor](./get_minor/)() const | Restituisce la versione secondaria. |
| **int16_t** [get_MinorRevision](./get_minorrevision/)() const | Restituisce il valore a 16 bit basso del numero di revisione. |
| int [get_Revision](./get_revision/)() const | Restituisce il numero di revisione. |
| int [GetHashCode](./gethashcode/)() const | Restituisce un codice hash per l'oggetto corrente. |
| static [Version](./) [Parse](./parse/)(const [String](../string/)\&) | Converte la rappresentazione stringa di un numero di versione in un'istanza equivalente della classe [Version](./). |
| [String](../string/) [ToString](./tostring/)() const | Restituisce la rappresentazione stringa del numero di versione rappresentato dall'oggetto corrente. |
| [String](../string/) [ToString](./tostring/)(int) const | Restituisce la rappresentazione stringa del numero specificato di sezioni del numero di versione rappresentato dall'oggetto corrente. |
|  [Version](./version/)(int, int, int, int) | Costruisce un'istanza che rappresenta i valori specificati di versione principale, secondaria, build e revisione. |
|  [Version](./version/)(int, int, int) | Costruisce un'istanza che rappresenta i valori specificati di versione principale, secondaria e build. |
|  [Version](./version/)(int, int) | Costruisce un'istanza che rappresenta i valori specificati di versione principale e valori. |
|  [Version](./version/)(const [String](../string/)\&) | Costruisce un'istanza che rappresenta il numero di versione rappresentato come stringa. |
|  [Version](./version/)() | Costruisce un'istanza che rappresenta il numero di versione 0.0.-1.-1. |

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)