---
title: Ref()
second_title: Aspose.Slides for C++ API Referencia
description: Referenciát hoz létre a DynamicWeakPtr objektumra. A fordító használja, amikor függvényargumentumokat referenciaként ad át.
type: docs
weight: 2458
url: /hu/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) függvény

Referencia létrehozása a(z) [DynamicWeakPtr](../dynamicweakptr/) objektumra. A fordító használja, amikor a függvényargumentumokat referenciaként adja át.

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Mutatott típus. |
| trunkMode | Az intelligens mutató saját módja. |
| weakLeafs | Azok a sablonargumentum-indexek, amelyekhez a SetTemplateWeakPtr metódust kell meghívni. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | Intelligens mutató, amelyhez referencia kerül létrehozásra. |

### Visszatérési érték

Intelligens mutató referencia.

## System::Ref(T\&) függvény

Segédfüggvény objektumokra való referenciák megszerzéséhez. Arra szolgál, hogy biztosítsa, hogy a(z) [System::DynamicWeakPtr](../dynamicweakptr/) a hozzárendelések után frissítse a hivatkozott objektumot.

```cpp
template<typename T> T & System::Ref(T &value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A típus, amelyhez referencia kerül létrehozásra. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | T\& | Az érték, amelyhez referencia kerül létrehozásra. |

### Visszatérési érték

Referencia az értékre, amelyet ezen függvénynek adtak át.

## Lásd még

* Osztály [DynamicWeakPtr](../dynamicweakptr/)
* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)