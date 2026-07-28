---
title: TryParse()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Konwertuje określony łańcuch zawierający reprezentację liczby w formie łańcucha na równoważną wartość zmiennoprzecinkową podwójnej precyzji.
type: docs
weight: 14
url: /pl/system/double/tryparse/
---
## Double::TryParse(const String\&, double\&) metoda


Konwertuje określony łańcuch zawierający reprezentację liczby w formie łańcucha na równoważną wartość zmiennoprzecinkową podwójnej precyzji.

```cpp
static bool System::Double::TryParse(const String &value, double &result)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Łańcuch do konwersji. |
| result | **double**\& | Odniesienie do zmiennej zmiennoprzecinkowej podwójnej precyzji, w której zostanie umieszczony wynik konwersji. |

### Wartość zwracana

Prawda, jeśli konwersja powiodła się, w przeciwnym razie – fałsz.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, double\&) metoda


Konwertuje określony łańcuch zawierający reprezentację liczby w formie łańcucha na równoważną wartość zmiennoprzecinkową podwójnej precyzji, używając dostarczonych informacji formatowania i stylu liczby.

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, double &result)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Łańcuch do konwersji. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinacja bitowa wartości wyliczenia NumberStyles określająca dozwolony styl reprezentacji liczby w łańcuchu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie łańcucha. |
| result | **double**\& | Odniesienie do zmiennej zmiennoprzecinkowej podwójnej precyzji, w której zostanie umieszczony wynik konwersji. |

### Wartość zwracana

Prawda, jeśli konwersja powiodła się, w przeciwnym razie – fałsz.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, double\&) metoda




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, double\&) metoda




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, double\&) metoda




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, double &result)
```

## Zobacz także

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)