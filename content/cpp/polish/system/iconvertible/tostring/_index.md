---
title: ToString()
second_title: Aspose.Slides dla C++ - odniesienie API
description: "Konwertuje wartość tej instancji na równoważny System::String przy użyciu określonych informacji o formatowaniu specyficznych dla kultury."
type: docs
weight: 196
url: /pl/system/iconvertible/tostring/
---
## IConvertible::ToString(System::SharedPtr\<System::IFormatProvider\>) metoda

Konwertuje wartość tego egzemplarza na równoważny [System::String](../../string/) przy użyciu określonych informacji formatowania specyficznych dla kultury.

```cpp
virtual System::String System::IConvertible::ToString(System::SharedPtr<System::IFormatProvider> provider)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Implementacja interfejsu [System::IFormatProvider](../../iformatprovider/), która dostarcza informacje formatowania specyficzne dla kultury. |

### Wartość zwracana

Instancja [System::String](../../string/) równoważna wartości tego egzemplarza.

## IConvertible::ToString() const metoda

Analog metody C# [Object.ToString()](../../object/tostring/). Umożliwia konwertowanie niestandardowych obiektów na ciąg znaków.

```cpp
virtual String System::Object::ToString() const
```

### Wartość zwracana

Reprezentacja [String](../../string/) dostarczona przez klasę końcową.

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [IConvertible](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)