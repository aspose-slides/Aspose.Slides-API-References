---
title: DynamicCastArray()
second_title: Aspose.Slides for C++ API referenciája
description: A megadott tömb elemeinek átkonvertálását más típusra hajtja végre.
type: docs
weight: 2991
url: /hu/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) függvény


Végrehajtja a megadott tömb elemeinek átkonvertálását más típusra.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| To | A típus, amelyre a megadott tömb elemeit át kell konvertálni |
| From | Az elemek típusa, amelyből a tömb elemeit át kell konvertálni |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | Megosztott mutató a konvertálandó elemeket tartalmazó tömbhöz |

### Visszatérési érték

Egy mutató egy új tömbre, amely **To** típusú elemeket tartalmaz, amelyek ekvivalensek a **from** elemeivel

Deprecated
:   Added for backward compatibility. Use ExplicitCast instead.

## Lásd még

* Typedef [SharedPtr](../sharedptr/)
* Osztály [Array](../array/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)