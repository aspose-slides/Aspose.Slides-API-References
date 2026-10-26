---
title: IsDefined()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: NIE ZREALIZOWANO. Określa, czy jeden lub więcej atrybutów określonego typu lub jego typów pochodnych jest zastosowane do tego elementu.
type: docs
weight: 157
url: /pl/system/typeinfo/isdefined/
---
## TypeInfo::IsDefined(const TypeInfo\&, bool) const metoda


NIE ZREALIZOWANO. Określa, czy jeden lub więcej atrybutów określonego typu lub jego typów pochodnych jest zastosowane do tego elementu.

```cpp
bool System::TypeInfo::IsDefined(const TypeInfo &attributeType, bool inherit) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Typ niestandardowego atrybutu, którego należy szukać. Wyszukiwanie obejmuje typy pochodne. |
| inherit | **bool** | true, aby przeszukać łańcuch dziedziczenia tego elementu w poszukiwaniu atrybutów; w przeciwnym razie false. Ten parametr jest ignorowany dla właściwości i zdarzeń. |

### Wartość zwracana

true, jeśli jeden lub więcej wystąpień attributeType lub któregokolwiek z jego typów pochodnych jest zastosowane do tego elementu; w przeciwnym razie false.

## Zobacz także

* Klasa [TypeInfo](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)