---
title: WeakReference<>
second_title: Aspose.Slides C++ API Referencia
description: Gyenge hivatkozást képvisel, amely egy objektumra mutat, miközben lehetővé teszi, hogy az objektum törlésre kerüljön.
type: docs
weight: 1522
url: /hu/system/weakreference_tmpl_end_tmpl/
---
## WeakReference<> osztály

Gyenge hivatkozást képvisel, amely utal egy objektumra, miközben lehetővé teszi, hogy az objektum törlésre kerüljön.

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | Megadja, hogy a jelenlegi WeakReference objektum által hivatkozott objektum törölve lett-e. |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | Visszaadja a jelenlegi WeakReference objektum által hivatkozott objektumot (a célt). |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Beállítja a jelenlegi WeakReference objektum által hivatkozott objektumot (a célt). |
| [WeakReference](./weakreference/)() | Alapértelmezett konstruktor. |
| [WeakReference](./weakreference/)(std::nullptr_t) | Konstruktor nullptr értékkel. |
| [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Inicializál egy új példányt a WeakReference osztályból, amely a megadott objektumra hivatkozik. |
| [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Inicializál egy új példányt a WeakReference osztályból, amely a megadott objektumra hivatkozik. |

## Lásd még

* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)