---
title: IsCppContainer
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Sprawdza, czy dany typ jest kontenerem w stylu STL. W tym celu sprawdza istnienie typów członkowskich iterator i const_iterator. Jeśli oba istnieją, dziedziczy std::true_type, w przeciwnym razie dziedziczy std::false_type."
type: docs
weight: 40
url: /pl/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer struct

Sprawdza, czy dany typ jest kontenerem w stylu STL. W tym celu sprawdza istnienie typów członkowskich iterator i const_iterator. Jeśli oba istnieją, dziedziczy std::true_type, w przeciwnym razie dziedziczy std::false_type.

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```

### Template parameters

| Parametr | Opis |
| --- | --- |
| T | Typ do sprawdzenia. |
| Enable | Formalny argument, aby SFINAE działało. |

## Zobacz także

* Przestrzeń nazw [System::TestPredicates::TypeTraits](../)
* Biblioteka [Aspose.Slides](../../)