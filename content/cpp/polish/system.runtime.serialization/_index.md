---
title: "System::Runtime::Serialization"
second_title: Aspose.Slides for C++ – dokumentacja API
description: 
type: docs
weight: 794
url: /pl/system.runtime.serialization/
---
## Klasy

| Klasa | Opis |
| --- | --- |
| [Details_SerializationException](./details_serializationexception/) |  |
| [FormatterConverter](./formatterconverter/) | Reprezentuje bazową implementację interfejsu [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/). |
| [IFormatterConverter](./iformatterconverter/) | Zapewnia połączenie między instancją [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) a klasą dostarczoną przez formatownik, najlepiej dopasowaną do parsowania danych wewnątrz [System::Runtime::Serialization::SerializationInfo](./serializationinfo/). |
| [ISerializable](./iserializable/) | Interfejs obiektu, który może być serializowany. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy czasu wykonywania i/lub błędy asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [SerializationInfo](./serializationinfo/) | Przechowuje zestaw nazwanych pól reprezentujących serializowany obiekt. Niezaimplementowane. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy czasu wykonywania i/lub błędy asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [StreamingContext](./streamingcontext/) | Klasa atrapy służąca do kompilacji przetłumaczonych klas używających StreamingContext. Nie zarządzaj instancjami tej klasy przy pomocy [SmartPtr](../system/smartptr/), muszą być przydzielane wyłącznie na stosie. |

## Definicje typów

| Definicja typu | Opis |
| --- | --- |
| [SerializationException](./serializationexception/) |  |