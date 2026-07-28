---
title: IsDefined()
second_title: Aspose.Slides C++ API referencia
description: NEM VALÓSÍTOTT. Jelzi, hogy a megadott típusú vagy annak származtatott típusaiban lévő egy vagy több attribútum alkalmazva van-e erre a tagra.
type: docs
weight: 157
url: /hu/system/typeinfo/isdefined/
---
## TypeInfo::IsDefined(const TypeInfo\&, bool) const metódus


NEM VALÓSÍTOTT. Jelzi, hogy a megadott típusú vagy annak származtatott típusaiban lévő egy vagy több attribútum alkalmazva van-e erre a tagra.

```cpp
bool System::TypeInfo::IsDefined(const TypeInfo &attributeType, bool inherit) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | A keresett egyedi attribútum típusa. A keresés magában foglalja a származtatott típusokat. |
| inherit | **bool** | true, ha a tag öröklési láncában keresendő az attribútum; egyébként false. Ez a paraméter tulajdonságok és események esetén figyelmen kívül marad. |

### Visszatérési érték

true, ha egy vagy több attributeType példány vagy annak bármely származtatott típusa alkalmazva van erre a tagra; egyébként false.

## Lásd még

* Osztály [TypeInfo](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)