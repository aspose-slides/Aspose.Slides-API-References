---
title: Enter()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Nabywa wyłączną blokadę na określonym obiekcie.
type: docs
weight: 1
url: /pl/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) metoda

Nabywa wyłączną blokadę na określonym obiekcie.

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Obiekt, na którym ma zostać nabyta blokada monitora. |

## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) metoda

Nabywa wyłączną blokadę na określonym obiekcie i atomowo ustawia wartość wskazującą, czy blokada została przyjęta.

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [Monitor](../)
* Przestrzeń nazw [System::Threading](../../)
* Biblioteka [Aspose.Slides](../../../)