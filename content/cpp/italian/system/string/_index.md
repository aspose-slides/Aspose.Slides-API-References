---
title: String
second_title: Riferimento API Aspose.Slides per C++
description: "Classe String utilizzata in tutta la libreria. È un sostituto di C# System.String durante la traduzione del codice. Per motivi di ottimizzazione, non è considerata una sottoclasse di Object. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe System::SmartPtr per gestire oggetti di questo tipo."
type: docs
weight: 1275
url: /it/system/string/
---
## Classe String

[String](./) classe usata in tutta la libreria. È un sostituto per C# [System.String](./) durante la traduzione del codice. Per motivi di ottimizzazione, non è considerata una sottoclasse di [Object](../object/). Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non usare mai la classe [System::SmartPtr](../smartptr/) per gestire oggetti di questo tipo.

```cpp
class String
```

## Metodi

| Method | Description |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./) è un tipo valore sul lato C++ che implicitamente (senza ereditarietà) implementa alcune interfacce. |
| const UChar * [begin](./begin/)() const | Restituisce un puntatore all'inizio del buffer reale della stringa. Non rialloca nulla. Non garantisce che il buffer sia terminato con null. |
| [String](./) [Clone](./clone/)() const | Crea una copia della stringa corrente. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | Confronta due sottostringhe con less-equal-greater. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Confronta due sottostringhe con less-equal-greater. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Confronta due sottostringhe con less-equal-greater. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | Confronta due sottostringhe con less-equal-greater. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | Confronta due sottostringhe con less-equal-greater. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Confronta due sottostringhe con less-equal-greater. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | Confronta due stringhe con less-equal-greater usando la modalità ordinale. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | Confronta due stringhe con less-equal-greater usando la modalità ordinale. |
| int [CompareTo](./compareto/)(const [String](./)\&) const | Confronta due stringhe nello stile 'less-equals-more'. Usa la cultura corrente. |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | Concatena le stringhe. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | Concatena le stringhe. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | Concatena le stringhe. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | Concatena le stringhe. |
| **bool** [Contains](./contains/)(const [String](./)\&) const | Verifica se str è una sottostringa della stringa corrente. |
| **bool** [Contains](./contains/)(char16_t) const | Verifica se la stringa contiene il carattere specificato. |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | Crea una copia della stringa. |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | Copia i caratteri della stringa in elementi di array esistenti. Non viene effettuato alcun ridimensionamento. |
| const UChar * [end](./end/)() const | Restituisce un puntatore alla fine del buffer reale della stringa. Non rialloca nulla. Non garantisce che il buffer sia terminato con null. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | Verifica se la stringa termina con la sottostringa specificata. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Verifica se la stringa termina con la sottostringa specificata. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Verifica se la stringa termina con la sottostringa specificata. |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | [String](./) confronto di uguaglianza. Sono supportate diverse modalità fornite dall'enumerazione StringComparison. |
| **bool** [Equals](./equals/)(const [String](./)\&) const | [String](./) confronto di uguaglianza. Usa la modalità di confronto [System::StringComparison::Ordinal](../stringcomparison/). |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | Confronta due stringhe per uguaglianza usando la modalità di confronto Ordial. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Confronta due stringhe per uguaglianza. |
| int [FastToAscii](./fasttoascii/)(char, int) const | Prova a convertire un [String](./) in una stringa ASCII. |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | Formatta la stringa in stile C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | Formatta la stringa in stile C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | Formatta la stringa in stile C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | Formatta la stringa in stile C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | Formatta la stringa in stile C#. |
| static [String](./) [FromAscii](./fromascii/)(const char *) | Crea [String](./) da una stringa ASCII. |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | Crea [String](./) da una stringa ASCII. |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | Crea [String](./) da una stringa ASCII. |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | Crea [String](./) da una stringa utf16. |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | Crea [String](./) da una stringa utf32. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | Crea [String](./) da una stringa utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | Crea [String](./) da una stringa utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | Crea [String](./) da una stringa utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | Crea [String](./) da una stringa utf8. |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | Crea [String](./) da una widestring. |
| int [get_Length](./get_length/)() const | Ottiene la lunghezza della stringa. |
| int [GetHashCode](./gethashcode/)() const | Calcola l'hash della stringa contenuta. Implementato in ICU, non corrisponde agli hash in C#. |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Ricerca in avanti di sottostringa. |
| int [IndexOf](./indexof/)(char_t, int) const | Ricerca in avanti di carattere. |
| int [IndexOf](./indexof/)(char_t, int, int) const | Ricerca in avanti di carattere nella sottostringa. |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | Ricerca in avanti di sottostringa. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Ricerca in avanti di sottostringa. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | Ricerca in avanti di sottostringa. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | Ricerca in avanti di sottostringa. |
| int [IndexOfAny](./indexofany/)(char_t, int) const | Ricerca in avanti di carattere. |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | Cerca quindi tutti i caratteri di str in questo. Se il primo carattere è trovato, viene restituita la sua posizione, altrimenti si cerca il secondo e così via. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Cerca qualsiasi dei caratteri passati in tutta la stringa. Confronta il primo carattere della stringa con tutti i caratteri in anyOf, poi il secondo e così via. Restituisce l'indice del primo carattere che corrisponde a uno dei caratteri target. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Cerca qualsiasi dei caratteri passati nella sottostringa. Confronta il primo carattere della stringa con tutti i caratteri in anyOf, poi il secondo e così via. Restituisce l'indice del primo carattere che corrisponde a uno dei caratteri target. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Cerca qualsiasi dei caratteri passati nella sottostringa. Confronta il primo carattere della stringa con tutti i caratteri in anyOf, poi il secondo e così via. Restituisce l'indice del primo carattere che corrisponde a uno dei caratteri target. |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | Inserisce una sottostringa nella posizione specificata. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Verifica se l'oggetto stringa è del tipo specificato da [TypeInfo](../typeinfo/) passato. |
| **bool** [IsAsciiString](./isasciistring/)() const | Indica se un [String](./) contiene solo simboli ASCII. |
| **bool** [IsEmpty](./isempty/)() const | Verifica se la stringa è sia non nulla sia vuota. |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Verifica se la stringa Unicode è normalizzata usando la forma di normalizzazione specificata. |
| **bool** [IsNull](./isnull/)() const | Verifica se la stringa è considerata null. [String](./) è null solo se è costruita tramite il costruttore [String()](./string/), spostata, copiata o assegnata da una stringa null o se è stato chiamato il metodo [reset()](./reset/). |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | Verifica se la stringa è vuota o è considerata null. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | Verifica se la stringa passata è null o vuota. |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | Indica se una stringa specificata è null, vuota o composta solo da caratteri di spazio bianco. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | Unisce l'array usando la stringa come separatore. |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | Unisce l'array usando la stringa come separatore. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | Unisce l'array usando la stringa come separatore. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | Unisce l'array usando la stringa come separatore. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | Ricerca all'indietro di sottostringa. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Ricerca all'indietro di sottostringa. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Ricerca all'indietro di sottostringa. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | Ricerca all'indietro di sottostringa. |
| int [LastIndexOf](./lastindexof/)(char_t) const | Ricerca all'indietro di carattere. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | Ricerca all'indietro di carattere. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | Ricerca all'indietro di carattere. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Cerca qualsiasi dei caratteri passati in tutta la stringa all'indietro. Confronta l'ultimo carattere della stringa con tutti i caratteri in anyOf, poi il precedente e così via. Restituisce l'indice della prima corrispondenza trovata. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Cerca qualsiasi dei caratteri passati nella sottostringa all'indietro. Confronta l'ultimo carattere della stringa con tutti i caratteri in anyOf, poi il precedente e così via. Restituisce l'indice della prima corrispondenza trovata. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Cerca qualsiasi dei caratteri passati nella sottostringa all'indietro. Confronta l'ultimo carattere della stringa con tutti i caratteri in anyOf, poi il precedente e così via. Restituisce l'indice della prima corrispondenza trovata. |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Normalizza la stringa Unicode usando la forma di normalizzazione specificata. |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | Converte la stringa in uno span di sola lettura. |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | Operatore di confronto non-uguaglianza. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Verifica se la stringa non è null. Applica la stessa logica della chiamata [IsNull()](./isnull/). |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | [String](./) operatore di concatenazione. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | [String](./) concatenazione con letterale di stringa o puntatore a stringa di caratteri. |
| [String](./) [operator+](./operator_plus/)(char_t) const | Aggiunge un carattere alla fine della stringa. |
| [String](./) [operator+](./operator_plus/)(int) const | Aggiunge la rappresentazione stringa di un valore intero alla fine della stringa. |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | Aggiunge la rappresentazione stringa di un valore intero senza segno alla fine della stringa. |
| [String](./) [operator+](./operator_plus/)(**double**) const | Aggiunge la rappresentazione stringa di un valore a virgola mobile alla fine della stringa. |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | Aggiunge la rappresentazione stringa di un valore intero a 64 bit alla fine della stringa. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Aggiunge la rappresentazione stringa di un oggetto di tipo riferimento alla fine della stringa. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Aggiunge la rappresentazione stringa di un oggetto di tipo riferimento alla fine della stringa. |
| [String](./) [operator+](./operator_plus/)(T) const | Aggiunge la rappresentazione stringa di un valore booleano alla fine della stringa. |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | Operatore di assegnazione di concatenazione. |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | Operatore di assegnazione di concatenazione. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | Operatore di assegnazione di concatenazione. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | Operatore di assegnazione di concatenazione. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | Operatore di assegnazione di concatenazione. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | Operatore di assegnazione di concatenazione. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | Operatore di assegnazione di concatenazione. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | Operatore di assegnazione di concatenazione. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | Operatore di assegnazione di concatenazione. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | Operatore di assegnazione di concatenazione. |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | Operatore di assegnazione di concatenazione. |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | Confronta le stringhe in ordine. |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | Operatore di assegnazione. |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | Operatore di assegnazione di spostamento. |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | Operatore di confronto di uguaglianza. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Verifica se la stringa è nulla. Applica la stessa logica della chiamata [IsNull()](./isnull/). |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | Confronta le stringhe in ordine. |
| char_t [operator[]](./operator[]/)(int) const | Ottiene il carattere nella posizione specificata. |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | Aggiunge riempimento a sinistra della stringa originale. |
| [String](./) [PadRight](./padright/)(int, char_t) const | Aggiunge riempimento a destra della stringa originale. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | Restituisce un iteratore inverso all'ultimo carattere (se presente) del buffer della stringa reale. |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | Estrae tutto tranne la sottostringa dalla stringa corrente. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | Restituisce un iteratore inverso al carattere precedente al primo (se presente) del buffer della stringa reale. |
| [String](./) [Replace](./replace/)(char_t, char_t) const | Sostituisce tutte le occorrenze del carattere nella stringa. |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | Sostituisce tutte le occorrenze della ricerca in questa stringa. |
| [String](./)\& [reset](./reset/)() | Imposta la stringa a null. È analogo a 'string_variable_name = null' in C#. |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | Imposta il carattere nella posizione specificata. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | Divide la stringa per carattere. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Divide la stringa per carattere. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | Divide la stringa per uno dei due caratteri. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Divide la stringa per uno dei caratteri specificati. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Divide la stringa per uno dei caratteri specificati. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | Divide la stringa per sottostringa. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Divide la stringa per sottostringa. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Divide la stringa per sottostringa. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Divide la stringa per sottostringa. Attualmente supporta solo un array di separatori di zero o un elemento. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | Verifica se la stringa inizia con la sottostringa specificata. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Verifica se la stringa inizia con la sottostringa specificata. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Verifica se la stringa inizia con la sottostringa specificata. |
|  [String](./string/)() | Costruttore predefinito. Crea un oggetto stringa considerato null. |
|  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | Costruisce una stringa basata su un literal di stringa. Considera il literal una stringa terminata da null, calcola la lunghezza della stringa target in base alla dimensione del literal. |
|  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | Costruisce una stringa basata su un puntatore a stringa di caratteri. Tratta la stringa puntata come terminata da null, calcola la lunghezza della stringa target in base al carattere null. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | Costruisce una stringa basata su un literal di stringa. Considera il literal una stringa terminata da null in UTF-8, calcola la lunghezza della stringa target in base alla dimensione del literal. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | Costruisce una stringa basata su un puntatore a stringa di caratteri. Tratta la stringa puntata come terminata da null in UTF-8, calcola la lunghezza della stringa target in base al carattere null. |
|  [String](./string/)(const char16_t *, int) | Costruisce una stringa da un puntatore a stringa di caratteri e una lunghezza esplicita. |
|  [String](./string/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) | Inizializza una nuova istanza della classe [System.String](./) con i caratteri Unicode indicati nello span di sola lettura specificato. |
|  [String](./string/)(const char *, int) | Costruisce una stringa da un puntatore a stringa di caratteri e una lunghezza esplicita. |
|  [String](./string/)(const char16_t *, int, int) | Costruisce una stringa dal puntatore a stringa di caratteri a partire da una posizione usando la lunghezza. |
| explicit  [String](./string/)(const char16_t, int) | Costruttore di riempimento. |
|  [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | Costruttore nullptr. Dichiarato come template per risolvere le priorità con altri costruttori template. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | Costruisce una stringa basata su un literal widestring. Considera il literal una stringa terminata da null, calcola la lunghezza della stringa target in base alla dimensione del literal. La conversione da **wchar_t** è dispendiosa su alcune piattaforme, quindi non sono consentite conversioni implicite. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | Costruisce una stringa basata su un puntatore a stringa widecharacter. Tratta la stringa puntata come terminata da null, calcola la lunghezza della stringa target in base al carattere null. La conversione da **wchar_t** è dispendiosa su alcune piattaforme, quindi non sono consentite conversioni implicite. |
| explicit  [String](./string/)(const **wchar_t** *, int) | Costruisce una stringa da un puntatore a stringa widecharacter e una lunghezza esplicita. La conversione da **wchar_t** è dispendiosa su alcune piattaforme, quindi non sono consentite conversioni implicite. |
| explicit  [String](./string/)(const **wchar_t**, int) | Costruttore di riempimento. La conversione da **wchar_t** è dispendiosa su alcune piattaforme, quindi non sono consentite conversioni implicite. |
|  [String](./string/)(const [String](./)\&) | Costruttore di copia. |
|  [String](./string/)([String](./)\&&) | Costruttore di spostamento. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | Converte l'intero array di caratteri in una stringa. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | Converte un sottointervallo dell'array di caratteri in una stringa. Se i parametri sono fuori dai limiti dell'array, viene costruita una stringa vuota. |
| explicit  [String](./string/)(const codeporting_icu::UnicodeString\&) | Avvolge UnicodeString in [String](./). |
| explicit  [String](./string/)(codeporting_icu::UnicodeString\&&) | Costruttore di spostamento. |
| explicit  [String](./string/)(const std::wstring\&) | Crea [String](./) da widestring. |
| explicit  [String](./string/)(const std::u16string\&) | Crea [String](./) da stringa utf16. |
| explicit  [String](./string/)(const std::string\&) | Crea [String](./) da stringa std::string presentata in formato UTF-8. |
| explicit  [String](./string/)(const std::u32string\&) | Crea [String](./) da stringa std::u32string. |
| [String](./) [Substring](./substring/)(**int32_t**) const | Estrae una sottostringa. |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | Estrae una sottostringa. |
| std::string [ToAsciiString](./toasciistring/)() const | Converte la stringa in std::string. Usa codifica ASCII. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | Converte la stringa o sottostringa in un array di byte. |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | Converte la stringa o sottostringa in un array di caratteri. |
| [String](./) [ToLower](./tolower/)() const | Converte tutti i caratteri della stringa in minuscolo. |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Converte tutti i caratteri della stringa in minuscolo usando una cultura specifica. |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | Converte tutti i caratteri della stringa in minuscolo usando la cultura invariante. |
| [String](./) [ToString](./tostring/)() const | Wrapper per gestire la classe [String](./) in contesti in cui [ToString()](./tostring/) è chiamata su oggetti di tipo valore. |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Wrapper per gestire la classe [String](./) in contesti in cui [ToString()](./tostring/) è chiamata su oggetti di tipo valore. |
| std::u16string [ToU16Str](./tou16str/)() const | Converte la stringa in std::u16string. |
| std::u32string [ToU32Str](./tou32str/)() const | Converte la stringa in std::u32string. |
| [String](./) [ToUpper](./toupper/)() const | Converte tutti i caratteri della stringa in maiuscolo. |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Converte tutti i caratteri della stringa in maiuscolo usando una cultura specifica. |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | Converte tutti i caratteri della stringa in maiuscolo usando la cultura invariante. |
| std::string [ToUtf8String](./toutf8string/)() const | Converte la stringa in std::string. Usa codifica UTF-8. |
| std::wstring [ToWCS](./towcs/)() const | Converte la stringa in std::wstring. |
| [String](./) [Trim](./trim/)() const | Rimuove tutti i caratteri di spaziatura sia dall'inizio che dalla fine della stringa. |
| [String](./) [Trim](./trim/)(char_t) const | Rimuove tutte le occorrenze del carattere passato sia dall'inizio che dalla fine della stringa. |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | Rimuove tutte le occorrenze dei caratteri passati sia dall'inizio che dalla fine della stringa. |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Rimuove tutte le occorrenze dei caratteri passati sia dall'inizio che dalla fine della stringa. |
| [String](./) [TrimEnd](./trimend/)() const | Rimuove tutti i caratteri di spaziatura dalla fine della stringa. |
| [String](./) [TrimEnd](./trimend/)(char_t) const | Rimuove tutte le occorrenze del carattere passato dalla fine della stringa. |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | Rimuove tutte le occorrenze dei caratteri passati dalla fine della stringa. |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Rimuove tutte le occorrenze dei caratteri passati dalla fine della stringa. |
| [String](./) [TrimStart](./trimstart/)() const | Rimuove tutti i caratteri di spaziatura dall'inizio della stringa. |
| [String](./) [TrimStart](./trimstart/)(char_t) const | Rimuove tutte le occorrenze del carattere passato dall'inizio della stringa. |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | Rimuove tutte le occorrenze dei caratteri passati dall'inizio della stringa. |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Rimuove tutte le occorrenze dei caratteri passati dall'inizio della stringa. |
| const UChar * [u_str](./u_str/)() const | Restituisce un buffer terminato da null in stile ICU. Può riallocare la stringa. |
|  [~String](./~string/)() | Distruttore. |

## Campi

| Campo | Descrizione |
| --- | --- |
| static [Empty](./empty/) | Stringa vuota. |
| static [Null](./null/) | Stringa nulla. |

## Typedef

| Typedef | Descrizione |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | Tipo di iteratore inverso. |

## Osservazioni



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // Costruisci una stringa dall'array di caratteri e stampala.
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // Costruisci una stringa dall'array di byte e stampala.
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // Rimuovi gli spazi dalla stringa sotto e stampala.
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // Stampa il numero di parole in .
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
Questo esempio di codice produce il seguente output:
hello
world
"This string contains whitespaces in the beginning and at the end."
Number of words: 11
*/
```

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)