---
title: With()
second_title: Aspose.Slides für C++ API-Referenz
description: Klont den Referenzdatensatz und wendet den Initialisierungsfunktor darauf an.
type: docs
weight: 2614
url: /de/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) Funktion


Kloniert den Referenzdatensatz und wendet den Initialisierungsfunktor darauf an.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Datensatztyp zum Klonen. |
| A | Initialisierungsfunktor-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | Gemeinsamer Zeiger auf das Objekt, das geklont und initialisiert werden soll. |
| initializer | const A\& | Initialisierungsfunktor, der auf die geklonte Aufzeichnung angewendet wird. |

### Rückgabewert

Gemeinsamer Zeiger auf den geklonten Datensatz.

## System::With(const T\&, const A\&) Funktion


Kopiert den Strukturdatensatz und wendet den Initialisierungsfunktor darauf an.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Datensatztyp zum Kopieren. |
| A | Initialisierungsfunktor-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| record | const T\& | Datensatz, der kopiert und initialisiert wird. |
| initializer | const A\& | Initialisierungsfunktor, der auf die Kopie des Datensatzes angewendet wird. |

### Rückgabewert

Kopierter Datensatz.

## Siehe auch

* Typedef [SharedPtr](../sharedptr/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)