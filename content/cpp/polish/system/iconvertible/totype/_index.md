---
title: ToType()
second_title: Aspose.Slides dla C++ Referencja API
description: "Konwertuje wartość tej instancji na System::Object określonego System::Type, który ma równoważną wartość, przy użyciu podanych informacji o formatowaniu zależnym od kultury."
type: docs
weight: 209
url: /pl/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) metoda


Konwertuje wartość tej instancji na [System::Object](../../object/) określonego System::Type, który ma równoważną wartość, używając podanych informacji o formatowaniu zależnym od kultury.

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```


### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | System::Type, do którego konwertowana jest wartość tej instancji. |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Implementacja interfejsu [System::IFormatProvider](../../iformatprovider/), która dostarcza informacje o formatowaniu zależnym od kultury. |

### Return Value

Instancja [System::Object](../../object/) typu conversionType, której wartość jest równoważna wartości tej instancji.

## See Also

* Definicja typu [SharedPtr](../../sharedptr/)
* Klasa [Object](../../object/)
* Klasa [TypeInfo](../../typeinfo/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [IConvertible](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)