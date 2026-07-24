---
title: UnboxToNullable()
second_title: Aspose.Slides für C++ API Referenz
description: Entpackt das Objekt in einen Nullable-Typ.
type: docs
weight: 79
url: /de/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) Methode

Entpackt das Objekt in einen Nullable-Typ.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) zum Entpacken. |
| safe | **bool** | Wenn true, gibt bei Fehler nullptr zurück, andernfalls wirft InvalidCastException. |

### Rückgabewert

Entpackter Nullable-Wert (kann null sein).

## Siehe auch

* Klasse [Nullable](../../nullable/)
* Klasse [SmartPtr](../../smartptr/)
* Klasse [Object](../../object/)
* Klasse [ObjectExt](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)