---
title: WeakReference<>
second_title: Aspose.Slides dla interfejsu API C++
description: Reprezentuje słabe odwołanie, które odwołuje się do obiektu, jednocześnie zezwalając na usunięcie tego obiektu.
type: docs
weight: 1522
url: /pl/system/weakreference_tmpl_end_tmpl/
---
## WeakReference<> klasa

Reprezentuje słabe odwołanie, które odwołuje się do obiektu, jednocześnie zezwalając na usunięcie tego obiektu.

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## Metody

| Metoda | Opis |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | Zwraca informację, czy obiekt odwoływany przez bieżący obiekt WeakReference został usunięty. |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | Zwraca obiekt (cel), na który odwołuje się bieżący obiekt WeakReference. |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Ustawia obiekt (cel), na który odwołuje się bieżący obiekt WeakReference. |
| [WeakReference](./weakreference/)() | Konstruktor domyślny. |
| [WeakReference](./weakreference/)(std::nullptr_t) | Konstruktor z nullptr. |
| [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Inicjalizuje nową instancję klasy WeakReference, odwołując się do określonego obiektu. |
| [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Inicjalizuje nową instancję klasy WeakReference, odwołując się do określonego obiektu. |
## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)