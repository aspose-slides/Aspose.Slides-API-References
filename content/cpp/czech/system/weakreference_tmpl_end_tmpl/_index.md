---
title: WeakReference<>
second_title: Aspose.Slides pro C++ - reference API
description: Representuje slabý odkaz, který odkazuje na objekt a zároveň umožňuje, aby byl tento objekt smazán.
type: docs
weight: 1522
url: /cs/system/weakreference_tmpl_end_tmpl/
---
## WeakReference<> třída

Representuje slabý odkaz, který odkazuje na objekt a zároveň umožňuje, aby byl tento objekt smazán.

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## Metody

| Metoda | Popis |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | Vrací informaci o tom, zda byl objekt odkazovaný aktuálním objektem WeakReference smazán. |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | Vrací objekt (cíl) odkazovaný aktuálním objektem WeakReference. |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Nastavuje objekt (cíl) odkazovaný aktuálním objektem WeakReference. |
|  [WeakReference](./weakreference/)() | Výchozí konstruktor. |
|  [WeakReference](./weakreference/)(std::nullptr_t) | Konstruktor z nullptr. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Inicializuje novou instanci třídy WeakReference, odkazující na zadaný objekt. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Inicializuje novou instanci třídy WeakReference, odkazující na zadaný objekt. |

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)