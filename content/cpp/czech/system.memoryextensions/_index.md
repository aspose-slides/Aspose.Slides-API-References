---
title: "System::MemoryExtensions"
second_title: Aspose.Slides pro C++ – reference API
description: Poskytuje rozšiřující metody pro operace s pamětí na spaních a polích.
type: docs
weight: 625
url: /cs/system.memoryextensions/
---
Poskytuje rozšiřující metody pro operace s pamětí na spanách a polích.

## Funkce

| Function | Popis |
| --- | --- |
| [Span](../system/span/)\<T\> [AsSpan](./asspan/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&, **int32_t**, **int32_t**) | Vytvoří span z pole. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [AsSpan](./asspan/)(const [String](../system/string/)\&, **int32_t**, **int32_t**) | Vytvoří span pouze ke čtení ze řetězce. |
| **int32_t** [BinarySearch](./binarysearch/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const TComparable\&) | Provede binární vyhledávání ve seřazeném spanu. |
| **int32_t** [BinarySearch](./binarysearch/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | Provede binární vyhledávání ve seřazeném spanu pomocí vlastního porovnávače. |
| **int32_t** [BinarySearch](./binarysearch/)(const [Span](../system/span/)\<T\>\&, const TComparable\&) | Provede binární vyhledávání v mutabilním seřazeném spanu. |
| **int32_t** [BinarySearch](./binarysearch/)(const [Span](../system/span/)\<T\>\&, const T\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | Provede binární vyhledávání v mutabilním seřazeném spanu pomocí vlastního porovnávače. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Najde délku společného prefixu mezi dvěma spany. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Najde délku společného prefixu mezi mutabilním spanu a spanu pouze ke čtení. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | Najde délku společného prefixu mezi dvěma mutabilními spany. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | Najde délku společného prefixu mezi dvěma spany pomocí vlastního porovnávače rovnosti. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | Najde délku společného prefixu mezi mutabilním spanu a spanu pouze ke čtení pomocí vlastního porovnávače rovnosti. |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | Najde délku společného prefixu mezi dvěma mutabilními spany pomocí vlastního porovnávače rovnosti. |
| **bool** [Contains](./contains/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Zkontroluje, zda span pouze ke čtení obsahuje konkrétní hodnotu. |
| **bool** [Contains](./contains/)(const [Span](../system/span/)\<T\>\&, const T\&) | Zkontroluje, zda mutabilní span obsahuje konkrétní hodnotu. |
| **bool** [Contains](./contains/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | Zkontroluje, zda znakový span obsahuje jiný znakový span se zadanými pravidly porovnání. |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Zkontroluje, zda span pouze ke čtení obsahuje některou ze dvou hodnot. |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | Zkontroluje, zda span pouze ke čtení obsahuje některou ze tří hodnot. |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Zkontroluje, zda mutabilní span obsahuje některou ze dvou hodnot. |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | Zkontroluje, zda mutabilní span obsahuje některou ze tří hodnot. |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Zkontroluje, zda span pouze ke čtení obsahuje nějakou hodnotu z jiného spanu. |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Zkontroluje, zda mutabilní span obsahuje nějakou hodnotu ze spanu pouze ke čtení. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | Zkontroluje, zda span pouze ke čtení obsahuje jakýkoli prvek kromě tří specifikovaných hodnot. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | Zkontroluje, zda mutabilní span obsahuje jakýkoli prvek kromě tří specifikovaných hodnot. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Zkontroluje, zda span pouze ke čtení obsahuje jakýkoli prvek kromě dvou specifikovaných hodnot. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Zkontroluje, zda mutabilní span obsahuje jakýkoli prvek kromě dvou specifikovaných hodnot. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Zkontroluje, zda span pouze ke čtení obsahuje jakýkoli prvek kromě specifikované hodnoty. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | Zkontroluje, zda mutabilní span obsahuje jakýkoli prvek kromě specifikované hodnoty. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Zkontroluje, zda span pouze ke čtení obsahuje jakýkoli prvek kromě těch v jiném spanu. |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Zkontroluje, zda mutabilní span obsahuje jakýkoli prvek kromě těch v spanu pouze ke čtení. |
| **bool** [ContainsAnyExceptInRange](./containsanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Zkontroluje, zda span pouze ke čtení obsahuje jakýkoli prvek mimo zadaný rozsah. |
| **bool** [ContainsAnyExceptInRange](./containsanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Zkontroluje, zda mutabilní span obsahuje jakýkoli prvek mimo zadaný rozsah. |
| **bool** [ContainsAnyInRange](./containsanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Zkontroluje, zda span pouze ke čtení obsahuje jakýkoli prvek v zadaném rozsahu. |
| **bool** [ContainsAnyInRange](./containsanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Zkontroluje, zda mutabilní span obsahuje jakýkoli prvek v zadaném rozsahu. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&, [Span](../system/span/)\<T\>\&) | Zkopíruje prvky z pole do spanu. |
| **int32_t** [Count](./count/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Spočítá výskyty hodnoty ve spanu pouze ke čtení. |
| **int32_t** [Count](./count/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Spočítá výskyty spanu v jiném spanu pouze ke čtení. |
| **int32_t** [Count](./count/)(const [Span](../system/span/)\<T\>\&, const T\&) | Spočítá výskyty jedné hodnoty ve Span<T> |
| **int32_t** [Count](./count/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Spočítá výskyty ReadOnlySpan<T> ve Span<T> |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Určuje, zda ReadOnlySpan<T> končí jedinou hodnotou. |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Určuje, zda ReadOnlySpan<T> končí jiným ReadOnlySpan<T> |
| **bool** [EndsWith](./endswith/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Určuje, zda Span<T> končí ReadOnlySpan<T> |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | Určuje, zda ReadOnlySpan<T> končí Span<T> |
| **bool** [EndsWith](./endswith/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | Určuje, zda Span<T> končí jiným Span<T> |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | Určuje, zda ReadOnlySpan<char16_t> končí zadanou hodnotou pomocí StringComparison. |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Najde index hodnoty ReadOnlySpan<T> v jiném ReadOnlySpan<T> |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Najde index jedné hodnoty v ReadOnlySpan<T> |
| **int32_t** [IndexOf](./indexof/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Najde index hodnoty ReadOnlySpan<T> ve Span<T> |
| **int32_t** [IndexOf](./indexof/)(const [Span](../system/span/)\<T\>\&, const T\&) | Najde index jedné hodnoty ve Span<T> |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | Najde index hodnoty ReadOnlySpan<char16_t> v ReadOnlySpan<char16_t> s použitím StringComparison. |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Najde index první výskytu kterékoliv ze dvou specifikovaných hodnot v ReadOnlySpan<T> |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | Najde index první výskytu kterékoliv ze tří specifikovaných hodnot v ReadOnlySpan<T> |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Najde index první výskytu kterékoliv ze dvou specifikovaných hodnot ve Span<T> |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | Najde index první výskytu kterékoliv ze tří specifikovaných hodnot ve Span<T> |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Najde index první výskytu jakékoli hodnoty ze spanu v jiném ReadOnlySpan<T> |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Najde index první výskytu jakékoli hodnoty ze spanu ve Span<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Najde index první výskytu prvního prvku, který není roven zadané hodnotě v ReadOnlySpan<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Najde index první výskytu prvního prvku, který není roven žádné ze dvou specifikovaných hodnot v ReadOnlySpan<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | Najde index první výskytu prvního prvku, který není roven žádné ze tří specifikovaných hodnot v ReadOnlySpan<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | Najde index první výskytu prvního prvku, který není roven zadané hodnotě ve Span<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Najde index první výskytu prvního prvku, který není roven žádné ze dvou specifikovaných hodnot ve Span<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | Najde index první výskytu prvního prvku, který není roven žádné ze tří specifikovaných hodnot ve Span<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Najde index prvního prvku, který není roven žádné hodnotě ve spanu hodnot. |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Najde index prvního prvku, který není roven žádné hodnotě ve spanu hodnot ve Span<T> |
| **int32_t** [IndexOfAnyExceptInRange](./indexofanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Najde index prvního prvku, který je mimo zadaný rozsah v ReadOnlySpan<T> |
| **int32_t** [IndexOfAnyExceptInRange](./indexofanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Najde index prvního prvku, který je mimo zadaný rozsah ve Span<T> |
| **int32_t** [IndexOfAnyInRange](./indexofanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Najde index prvního prvku, který je v zadaném rozsahu v ReadOnlySpan<T> |
| **int32_t** [IndexOfAnyInRange](./indexofanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Najde index prvního prvku, který je v zadaném rozsahu ve Span<T> |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Najde poslední výskyt sekvence ve spanu. |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Najde poslední výskyt jedné hodnoty ve spanu. |
| **int32_t** [LastIndexOf](./lastindexof/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Najde poslední výskyt sekvence v mutabilním spanu. |
| **int32_t** [LastIndexOf](./lastindexof/)(const [Span](../system/span/)\<T\>\&, const T\&) | Najde poslední výskyt jedné hodnoty v mutabilním spanu. |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | Najde poslední výskyt hodnoty ve spanu pomocí zadaného porovnání řetězců. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | Najde poslední výskyt kterékoliv ze tří specifikovaných hodnot ve spanu. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | Najde poslední výskyt kterékoliv ze tří specifikovaných hodnot v mutabilním spanu. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Najde poslední výskyt kterékoliv ze dvou specifikovaných hodnot ve spanu. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Najde poslední výskyt kterékoliv ze dvou specifikovaných hodnot v mutabilním spanu. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Najde poslední výskyt jakékoli hodnoty ze sekvence ve spanu. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Najde poslední výskyt jakékoli hodnoty ze sekvence v mutabilním spanu. |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | Najde poslední výskyt jakékoli hodnoty z mutabilní sekvence v mutabilním spanu. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | Najde poslední výskyt libovolného prvku kromě tří zadaných hodnot v rozsahu. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | Najde poslední výskyt libovolného prvku kromě tří zadaných hodnot v mutovatelném rozsahu. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Najde poslední výskyt libovolného prvku kromě dvou zadaných hodnot v rozsahu. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Najde poslední výskyt libovolného prvku kromě dvou zadaných hodnot v mutovatelném rozsahu. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Najde poslední výskyt libovolného prvku kromě zadané hodnoty v rozsahu. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | Najde poslední výskyt libovolného prvku kromě zadané hodnoty v mutovatelném rozsahu. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Najde poslední výskyt libovolného prvku kromě hodnot ze sekvence v rozsahu. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Najde poslední výskyt libovolného prvku kromě hodnot ze sekvence v mutovatelném rozsahu. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | Najde poslední výskyt libovolného prvku kromě hodnot z mutovatelné sekvence v mutovatelném rozsahu. |
| **int32_t** [LastIndexOfAnyExceptInRange](./lastindexofanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Najde poslední výskyt libovolného prvku mimo určený rozsah v rozsahu. |
| **int32_t** [LastIndexOfAnyExceptInRange](./lastindexofanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Najde poslední výskyt libovolného prvku mimo určený rozsah v mutovatelném rozsahu. |
| **int32_t** [LastIndexOfAnyInRange](./lastindexofanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | Najde poslední výskyt libovolného prvku v určeném rozsahu v rozsahu. |
| **int32_t** [LastIndexOfAnyInRange](./lastindexofanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Najde poslední výskyt libovolného prvku v určeném rozsahu v mutovatelném rozsahu. |
| **bool** [Overlaps](./overlaps/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Určuje, zda se dvě ReadOnlySpans překrývají v paměti bez výpočtu offsetu. |
| **bool** [Overlaps](./overlaps/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Určuje, zda se [Span](../system/span/) a [ReadOnlySpan](../system/readonlyspan/) překrývají v paměti bez výpočtu offsetu. |
| **bool** [Overlaps](./overlaps/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**\&) | Určuje, zda se dvě ReadOnlySpans překrývají v paměti a vypočítá offset. |
| **bool** [Overlaps](./overlaps/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**\&) | Určuje, zda se [Span](../system/span/) a [ReadOnlySpan](../system/readonlyspan/) překrývají v paměti a vypočítá offset. |
| void [Replace](./replace/)([Span](../system/span/)\<T\>\&, const T\&, const T\&) | Nahrazuje všechny výskyty hodnoty novou hodnotou v [Span](../system/span/). |
| void [Replace](./replace/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [Span](../system/span/)\<T\>\&, const T\&, const T\&) | Kopíruje prvky ze zdroje do cíle a během kopírování nahrazuje zadané hodnoty. |
| void [Reverse](./reverse/)([Span](../system/span/)\<T\>\&) | Obrátí pořadí prvků v [Span](../system/span/) na místě. |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Porovnává dva ReadOnlySpany lexikograficky. |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Porovnává [Span](../system/span/) a [ReadOnlySpan](../system/readonlyspan/) lexikograficky. |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | Porovnává [ReadOnlySpan](../system/readonlyspan/) a [Span](../system/span/) lexikograficky. |
| **bool** [SequenceEqual](./sequenceequal/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Určuje, zda dva ReadOnlySpany obsahují identické prvky ve stejném pořadí. |
| **bool** [SequenceEqual](./sequenceequal/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Určuje, zda [Span](../system/span/) a [ReadOnlySpan](../system/readonlyspan/) obsahují identické prvky ve stejném pořadí. |
| **bool** [SequenceEqual](./sequenceequal/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | Určuje, zda dva ReadOnlySpany obsahují stejné prvky pomocí vlastního porovnávače. |
| **bool** [SequenceEqual](./sequenceequal/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | Určuje, zda [Span](../system/span/) a [ReadOnlySpan](../system/readonlyspan/) obsahují stejné prvky pomocí vlastního porovnávače. |
| void [Sort](./sort/)(const [Span](../system/span/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | Řadí [Span](../system/span/) pomocí vlastního porovnávače. |
| void [Sort](./sort/)([Span](../system/span/)\<T\>\&) | Řadí [Span](../system/span/) pomocí výchozího porovnání. |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | Řadí páry klíč-hodnota pomocí vlastního porovnávače (klíče a hodnoty jsou řazeny společně) |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, [System::Comparison](../system/comparison/)\<TKey\>) | Řadí páry klíč-hodnota pomocí delegáta porovnání. |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&) | Řadí páry klíč-hodnota pomocí výchozího porovnání. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Kontroluje, zda rozsah začíná zadanou hodnotou. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Kontroluje, zda rozsah začíná zadaným rozsahem hodnot. |
| **bool** [StartsWith](./startswith/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Kontroluje, zda mutovatelný rozsah začíná zadaným read-only rozsahem hodnot. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | Kontroluje, zda read-only rozsah začíná zadaným mutovatelným rozsahem hodnot. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | Kontroluje, zda znakový rozsah začíná zadaným rozsahem hodnot pomocí porovnání řetězců. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<[String](../system/string/)\>\&, const char16_t *) | Kontroluje, zda řetězcový rozsah začíná zadaným polem znaků. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, T) | Ořízne zadaný prvek z obou konců typovaného rozsahu. |
| [Span](../system/span/)\<T\> [Trim](./trim/)([Span](../system/span/)\<T\>\&, T) | Ořízne zadaný prvek z obou konců mutovatelného typovaného rozsahu. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Ořízne zadané prvky z obou konců typovaného rozsahu. |
| [Span](../system/span/)\<T\> [Trim](./trim/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Ořízne zadané prvky z obou konců mutovatelného typovaného rozsahu. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | Ořízne bílé znaky z obou konců znakového rozsahu. |
| [Span](../system/span/)\<char16_t\> [Trim](./trim/)([Span](../system/span/)\<char16_t\>\&) | Ořízne bílé znaky z obou konců mutovatelného znakového rozsahu. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Ořízne zadaný prvek z konce typovaného rozsahu. |
| [Span](../system/span/)\<T\> [TrimEnd](./trimend/)([Span](../system/span/)\<T\>\&, const T\&) | Ořízne zadaný prvek z konce mutovatelného typovaného rozsahu. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Ořízne zadané prvky z konce typovaného rozsahu. |
| [Span](../system/span/)\<T\> [TrimEnd](./trimend/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Ořízne zadané prvky z konce mutovatelného typovaného rozsahu. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | Ořízne bílé znaky z konce znakového rozsahu. |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&) | Ořízne bílé znaky z konce mutovatelného znakového rozsahu. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, char16_t) | Ořízne zadaný znak z konce znakového rozsahu. |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&, char16_t) | Ořízne zadaný znak z konce mutovatelného znakového rozsahu. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | Ořízne zadané znaky z konce znakového rozsahu. |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | Ořízne zadané znaky z konce mutovatelného znakového rozsahu. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | Ořízne zadaný prvek ze začátku typovaného rozsahu. |
| [Span](../system/span/)\<T\> [TrimStart](./trimstart/)([Span](../system/span/)\<T\>\&, const T\&) | Ořízne zadaný prvek ze začátku mutovatelného typovaného rozsahu. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Ořízne zadané prvky ze začátku typovaného rozsahu. |
| [Span](../system/span/)\<T\> [TrimStart](./trimstart/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | Ořízne zadané prvky ze začátku mutovatelného typovaného rozsahu. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | Ořízne bílé znaky ze začátku znakového rozsahu. |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&) | Ořízne bílé znaky ze začátku mutovatelného znakového rozsahu. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, char16_t) | Ořízne zadaný znak ze začátku znakového rozsahu. |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&, char16_t) | Ořízne zadaný znak ze začátku mutovatelného znakového rozsahu. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | Ořízne zadané znaky ze začátku znakového rozsahu. |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | Ořízne zadané znaky ze začátku mutovatelného znakového rozsahu. |
| **int32_t** [CompareTo](./compareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | Porovnává dva znakové rozsahy podle zadaných pravidel porovnání řetězců. |
| **bool** [Equals](./equals/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | Porovnává dva ReadOnlySpan<char16_t> na rovnost pomocí StringComparison. |
| **bool** [IsWhiteSpace](./iswhitespace/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | Kontroluje, zda celý rozsah obsahuje jen bílé znaky. |
| **int32_t** [ToLower](./tolower/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&, const [SharedPtr](../system/sharedptr/)\<[Globalization::CultureInfo](../system.globalization/cultureinfo/)\>\&) | Převede znaky na malé písmo pomocí zadané kultury. |
| **int32_t** [ToLowerInvariant](./tolowerinvariant/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&) | Převede znaky na malé písmo pomocí invariantní kultury. |
| **int32_t** [ToUpper](./toupper/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&, const [SharedPtr](../system/sharedptr/)\<[Globalization::CultureInfo](../system.globalization/cultureinfo/)\>\&) | Převede znaky na velké písmo pomocí zadané kultury. |
| **int32_t** [ToUpperInvariant](./toupperinvariant/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&) | Převede znaky na velké písmo pomocí invariantní kultury. |