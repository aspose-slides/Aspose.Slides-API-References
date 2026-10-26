---
title: Ref()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine Referenz auf ein DynamicWeakPtr-Objekt. Wird vom Übersetzer verwendet, wenn Funktionsargumente per Referenz übergeben werden.
type: docs
weight: 2458
url: /de/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) Funktion

Erstellt eine Referenz auf das Objekt [DynamicWeakPtr](../dynamicweakptr/). Wird vom Übersetzer verwendet, wenn Funktionsargumente per Referenz übergeben werden.

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Zieltyp. |
| trunkMode | Modus des Smart-Pointers selbst. |
| weakLeafs | Indizes der Template-Argumente, für die die Methode SetTemplateWeakPtr aufgerufen werden muss. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | Smart-Pointer, zu dem eine Referenz erstellt werden soll. |

### Rückgabewert

Smart-Pointer-Referenz.

## System::Ref(T\&) Funktion

Hilfsfunktion zum Erwerben von Referenzen auf Objekte. Wird verwendet, um sicherzustellen, dass [System::DynamicWeakPtr](../dynamicweakptr/) das referenzierte Objekt nach Zuweisungen aktualisiert.

```cpp
template<typename T> T & System::Ref(T &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ, für den eine Referenz erstellt werden soll. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | T\& | Wert, zu dem eine Referenz erstellt werden soll. |

### Rückgabewert

Referenz auf den an diese Funktion übergebenen Wert.

## Siehe auch

* Klasse [DynamicWeakPtr](../dynamicweakptr/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)