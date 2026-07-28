---
title: TryParse()
second_title: Aspose.Slides dla C++ – odniesienie do API
description: Konwertuje podany ciąg zawierający reprezentację liczby w postaci łańcucha na równoważną wartość Decimal.
type: docs
weight: 482
url: /pl/system/decimal/tryparse/
---

## Decimal::TryParse(const String\&, Decimal\&) metoda

Konwertuje podany ciąg zawierający reprezentację liczby w postaci łańcucha na równoważną wartość [Decimal](../).

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg do konwersji |
| result | [Decimal](../)\& | Referencja do zmiennej [Decimal](../), w której zostanie umieszczony wynik konwersji |

### Wartość zwracana

True, jeśli konwersja się powiodła, w przeciwnym razie - false

## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) metoda

Konwertuje podany ciąg zawierający reprezentację liczby w postaci łańcucha na równoważną wartość [Decimal](../) przy użyciu dostarczonych informacji o formatowaniu i stylu liczby.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg do konwersji |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dopuszczalny styl reprezentacji liczby w postaci ciągu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu |
| result | [Decimal](../)\& | Argument wyjściowy; zawiera wynik konwersji |

### Wartość zwracana

True, jeśli konwersja się powiodła, w przeciwnym razie - false

## Zobacz także

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Decimal](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)