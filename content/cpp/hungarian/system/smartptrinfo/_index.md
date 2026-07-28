---
title: SmartPtrInfo
second_title: Aspose.Slides C++ API referenciája
description: Szolgáltató osztály a SmartPtr tartalmának tesztelésére és módosítására anélkül, hogy ismernénk a végső típust. A szemétgyűjtéshez és a ciklus hivatkozások felderítéséhez stb. használják. Gondoljunk rá úgy, mint 'pointer to pointer'-re. Nem használhatjuk a SmartPtr alaptípusát, mivel nincs ilyen; helyette ezt az 'info' osztályt használjuk.
type: docs
weight: 1249
url: /hu/system/smartptrinfo/
---
## SmartPtrInfo osztály


Szolgáltató osztály a(z) [SmartPtr](../smartptr/) tartalmának tesztelésére és módosítására anélkül, hogy ismernénk a végső típust. A szemétgyűjtéshez és a ciklus hivatkozások észleléséhez stb. használják. Gondoljunk rá úgy, mint „pointer to pointer”-re. Nem használhatjuk a(z) [SmartPtr](../smartptr/) alaptípusát, mivel nincs ilyen; helyette ezt az „info” osztályt használjuk.

```cpp
class SmartPtrInfo
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | Megkapja a nyers objektumra mutató hivatkozott pointert. |
| [Object](../object/) * [getObject](./getobject/)() const | Megkapja az objektumra mutató hivatkozott pointert. |
| [Object](../object/) * [getOwned](./getowned/)() const | Megkapja a tulajdonolt objektum pointert. |
| [operator bool](./operator_bool/)() const | Ellenőrzi, hogy az info objektum nem null pointerre mutat-e. |
| **bool** [operator!](./operator_not/)() const | Ellenőrzi, hogy az info objektum nem mutat-e nem null pointerre. |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | Lehetővé teszi, hogy a hivatkozott pointer által mutatott [Object](../object/) metódusait hívjuk. |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | Összehasonlítja két info objektum által hivatkozott pointerek értékeit. |
| [SmartPtrInfo](./smartptrinfo/)() | Üres [SmartPtrInfo](./) objektumot hoz létre. |
| explicit [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | [SmartPtrInfo](./) objektumot hoz létre egy adott okos pointerrel kapcsolatos információval. |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)