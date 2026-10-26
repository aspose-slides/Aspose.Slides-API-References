---
title: Decimal
second_title: Riferimento API Aspose.Slides per C++
description: "Rappresenta un numero decimale. Questo tipo dovrebbe essere allocato nello stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe System::SmartPtr per gestire oggetti di questo tipo."
type: docs
weight: 261
url: /it/system/decimal/
---
## Decimal classe

Rappresenta un numero decimale. Questo tipo dovrebbe essere allocato nello stack e passato alle funzioni per valore o per riferimento. Non usare mai [System::SmartPtr](../smartptr/) classe per gestire oggetti di questo tipo.

```cpp
class Decimal
```

## Metodi

| Method | Description |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | Aggiunge due valori [Decimal](./) specificati. |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | Restituisce il più piccolo valore intero maggiore o uguale al valore specificato. |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | Determina se il valore rappresentato dal primo oggetto [Decimal](./) è minore, uguale o maggiore del valore rappresentato dal secondo oggetto [Decimal](./). |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | Determina se il valore rappresentato dall'oggetto corrente è minore, uguale o maggiore del valore rappresentato dall'oggetto specificato. |
|  [Decimal](./decimal/)() | Crea un'istanza che rappresenta 0. |
|  [Decimal](./decimal/)(std::int8_t) | Crea un'istanza che rappresenta il valore specificato. |
|  [Decimal](./decimal/)(std::int16_t) | Crea un'istanza che rappresenta il valore specificato. |
|  [Decimal](./decimal/)(std::int32_t) | Crea un'istanza che rappresenta il valore specificato. |
|  [Decimal](./decimal/)(std::int64_t) | Crea un'istanza che rappresenta il valore specificato. |
|  [Decimal](./decimal/)(std::uint8_t) | Crea un'istanza che rappresenta il valore specificato. |
|  [Decimal](./decimal/)(std::uint16_t) | Crea un'istanza che rappresenta il valore specificato. |
|  [Decimal](./decimal/)(std::uint32_t) | Crea un'istanza che rappresenta il valore specificato. |
|  [Decimal](./decimal/)(std::uint64_t) | Crea un'istanza che rappresenta il valore specificato. |
|  [Decimal](./decimal/)(**float**) | Crea un'istanza che rappresenta il valore specificato. |
|  [Decimal](./decimal/)(**double**) | Crea un'istanza che rappresenta il valore specificato. |
| explicit  [Decimal](./decimal/)(const std::string\&) | Crea un'istanza che rappresenta un valore la cui rappresentazione stringa è specificata come un'istanza della classe std::string. |
|  [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | Crea un oggetto [Decimal](./) dai componenti specificati. |
|  [Decimal](./decimal/)(const [Decimal](./)\&) | Crea un'istanza della classe [Decimal](./) che rappresenta lo stesso numero dell'oggetto [Decimal](./) specificato. |
|  [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | Crea un'istanza della classe [Decimal](./) da un array di interi contenente una rappresentazione binaria. |
|  [Decimal](./decimal/)(std::nullptr_t) | Lancia sempre ArgumentNullException. |
|  [Decimal](./decimal/)(const [number_type](./number_type/)\&) | Crea un'istanza della classe [Decimal](./) che rappresenta il valore specificato. |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | Dividi due valori [Decimal](./) specificati. |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | Determina se i valori rappresentati dall'oggetto corrente e dall'oggetto specificato sono uguali. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Determina se i valori rappresentati dall'oggetto corrente e dall'oggetto specificato sono uguali. |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | Determina se i valori rappresentati dagli oggetti specificati sono uguali. |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | Restituisce il più grande valore intero minore o uguale al valore specificato. |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) il valore OLE currency specificato al valore [Decimal](./) equivalente. NON IMPLEMENTATO. |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | Converte l'oggetto [Decimal](./) specificato nella rappresentazione binaria del valore che rappresenta. |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) il valore [Decimal](./) specificato in un array di byte. |
| int [GetHashCode](./gethashcode/)() const | Restituisce un codice hash per l'oggetto corrente. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | Ottiene il codice di tipo dell'oggetto. |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | Moltiplica due valori [Decimal](./) specificati. |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | Restituisce una nuova istanza della classe [Decimal](./) che rappresenta un valore risultante dalla negazione del valore rappresentato dall'oggetto specificato. |
| explicit  [operator bool](./operator_bool/)() const | Converte il valore rappresentato dall'oggetto corrente in un valore booleano. |
| explicit  [operator double](./operator_double/)() const | Converte il valore rappresentato dall'oggetto corrente in un valore a virgola mobile a doppia precisione. |
| explicit  [operator float](./operator_float/)() const | Converte il valore rappresentato dall'oggetto corrente in un valore a virgola mobile a precisione singola. |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | Determina se i valori rappresentati dall'oggetto corrente e dall'oggetto specificato sono diversi. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Determina se il valore rappresentato dall'oggetto corrente è diverso da 0. |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | Restituisce una nuova istanza della classe [Decimal](./) che rappresenta un valore risultato dell'operazione modulo tra i valori rappresentati dall'oggetto corrente e da quello specificato. |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | Assegna all'oggetto corrente un nuovo valore risultato dell'operazione modulo tra i valori rappresentati dall'oggetto corrente e da quello specificato. |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | Restituisce una nuova istanza della classe [Decimal](./) che rappresenta un valore risultato della moltiplicazione dei valori rappresentati dall'oggetto corrente e da quello specificato. |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | Assegna all'oggetto corrente un nuovo valore risultato della moltiplicazione dei valori rappresentati dall'oggetto corrente e da quello specificato. |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | Restituisce una nuova istanza della classe [Decimal](./) che rappresenta un valore che è la somma dei valori rappresentati dall'oggetto corrente e da quello specificato. |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | Incrementa il valore rappresentato dall'oggetto corrente. |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | Assegna all'oggetto corrente un nuovo valore che è la somma dei valori rappresentati dall'oggetto corrente e da quello specificato. |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | Restituisce una nuova istanza della classe [Decimal](./) che rappresenta un valore risultato della sottrazione del valore rappresentato dall'oggetto specificato dal valore rappresentato dall'oggetto corrente. |
| [Decimal](./) [operator-](./operator_minus/)() const | Restituisce una nuova istanza della classe [Decimal](./) che rappresenta un valore risultato dalla negazione del valore rappresentato dall'oggetto corrente. |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | Decrementa il valore rappresentato dall'oggetto corrente. |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | Assegna all'oggetto corrente un nuovo valore risultato della sottrazione del valore rappresentato dall'oggetto specificato dal valore rappresentato dall'oggetto corrente. |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | Restituisce una nuova istanza della classe [Decimal](./) che rappresenta un valore risultato della divisione del valore rappresentato dall'oggetto corrente per il valore rappresentato dall'oggetto specificato. |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | Assegna all'oggetto corrente un nuovo valore risultato della divisione del valore rappresentato dall'oggetto corrente per il valore rappresentato dall'oggetto specificato. |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | Determina se il valore rappresentato dall'oggetto corrente è minore del valore rappresentato dall'oggetto specificato. |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | Determina se il valore rappresentato dall'oggetto corrente è minore o uguale al valore rappresentato dall'oggetto specificato. |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | Assegna il valore rappresentato dall'oggetto specificato all'oggetto corrente. |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | Determina se i valori rappresentati dall'oggetto corrente e dall'oggetto specificato sono uguali. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Determina se il valore rappresentato dall'oggetto corrente è 0. |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | Determina se il valore rappresentato dall'oggetto corrente è maggiore del valore rappresentato dall'oggetto specificato. |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | Determina se il valore rappresentato dall'oggetto corrente è maggiore o uguale al valore rappresentato dall'oggetto specificato. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | Converte la rappresentazione stringa di un numero decimale in un'istanza equivalente della classe [Decimal](./). |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | Converte la rappresentazione stringa di un numero decimale in un'istanza equivalente della classe [Decimal](./) usando lo stile specificato. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la rappresentazione stringa di un numero decimale in un'istanza equivalente della classe [Decimal](./) usando il provider di formattazione specificato. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converte la rappresentazione stringa di un numero decimale in un'istanza equivalente della classe [Decimal](./) usando lo stile e il provider di formattazione specificati. |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | Calcola il resto dopo la divisione di due valori [Decimal](./). |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | Arrotonda il valore specificato al numero intero più vicino. Un parametro specifica il comportamento della funzione se il valore specificato è equidistante dai due numeri più vicini. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | Arrotonda il valore specificato al valore più vicino con il numero specificato di cifre frazionarie. Un parametro specifica il comportamento della funzione se il valore specificato è equidistante dai due valori più vicini. |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | Sottrae un valore [Decimal](./) specificato da un altro. |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | Converte il valore [Decimal](./) in un valore intero senza segno a 8 bit. |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | Converte il valore [Decimal](./) in un numero a virgola mobile a doppia precisione. |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | Converte il valore [Decimal](./) in un valore intero con segno a 16 bit. |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | Converte il valore [Decimal](./) in un valore intero con segno a 32 bit. |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | Converte il valore [Decimal](./) in un valore intero con segno a 64 bit. |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) il valore [Decimal](./) specificato al valore OLE currency equivalente. NON IMPLEMENTATO. |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | Converte il valore [Decimal](./) in un valore intero con segno a 8 bit. |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | Converte il valore [Decimal](./) in un numero a virgola mobile a precisione singola. |
| std::string [ToStdString](./tostdstring/)() const | Restituisce un'istanza di std::string che contiene la rappresentazione stringa del valore rappresentato dall'oggetto. |
| [String](../string/) [ToString](./tostring/)() const | Restituisce la rappresentazione stringa del valore rappresentato dall'oggetto. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Converte l'oggetto corrente in stringa usando le informazioni di formattazione specifiche della cultura. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Converte l'oggetto corrente nella sua rappresentazione stringa usando il formato stringa specificato e le informazioni di formattazione specifiche della cultura fornite dall'oggetto [IFormatProvider](../iformatprovider/) specificato. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | Restituisce la rappresentazione stringa del valore rappresentato dall'oggetto. Per uso interno. |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | Converte il valore [Decimal](./) in un valore intero senza segno a 16 bit. |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | Converte il valore [Decimal](./) in un valore intero senza segno a 32 bit. |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | Converte il valore [Decimal](./) in un valore intero senza segno a 64 bit. |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | Restituisce l'oggetto [Decimal](./) che rappresenta un valore la cui parte intera è uguale a quella del valore rappresentato dall'oggetto [Decimal](./) specificato, con tutte le cifre frazionarie scartate. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | Converte la stringa specificata contenente la rappresentazione stringa di un numero nel valore [Decimal](./) equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | Converte la stringa specificata contenente la rappresentazione stringa di un numero nel valore [Decimal](./) equivalente usando le informazioni di formattazione e lo stile numerico forniti. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Restituisce un riferimento all'oggetto [TypeInfo](../typeinfo/) che rappresenta le informazioni di tipo della classe [Decimal](./). |
|  [~Decimal](./~decimal/)() | Distruttore. |

## Campi

| Field | Description |
| --- | --- |
| static [MaxValue](./maxvalue/) | Rappresenta il numero più grande che può essere rappresentato dalla classe [Decimal](./). |
| static [MinusOne](./minusone/) | Rappresenta il numero -1. |
| static [MinValue](./minvalue/) | Rappresenta il più piccolo numero che può essere rappresentato dalla classe [Decimal](./). |
| static [One](./one/) | Rappresenta il numero 1. |
| static [Zero](./zero/) | Rappresenta il numero 0. |

## Alias di tipo

| Typedef | Description |
| --- | --- |
| [number_type](./number_type/) | Un alias per Detail::decimal_number_type. |

## Osservazioni



```cpp
#include "system/console.h"
#include "system/decimal.h"

int main()
{
  using namespace System;

  Console::WriteLine(Decimal::MinValue);
  Console::WriteLine(Decimal::MaxValue);

  auto dividend = Decimal::One;
  auto divisor = 6;
  Console::WriteLine(dividend/divisor);

  return 0;
}
/*
Questo esempio di codice produce il seguente output:
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)