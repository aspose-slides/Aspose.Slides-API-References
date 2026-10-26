---
title: ToSingle()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert vier Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen Gleitkommawert mit einfacher Genauigkeit.
type: docs
weight: 131
url: /de/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) Methode


Konvertiert vier Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen Gleitkommawert mit einfacher Genauigkeit.

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) die Bytes enthält, die konvertiert werden sollen |
| startIndex | int | [Index](../../index/) im Array, ab dem Bytes für die Konvertierung entnommen werden |

### Rückgabewert

Gleitkommawert mit einfacher Genauigkeit, der durch die Konvertierung entsteht

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) Methode


Konvertiert vier Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen Gleitkommawert mit einfacher Genauigkeit.

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, das Bytes enthält, die konvertiert werden sollen |
| startIndex | int | [Index](../../index/) im Array, ab dem Bytes für die Konvertierung entnommen werden |

### Rückgabewert

Gleitkommawert mit einfacher Genauigkeit, der durch die Konvertierung entsteht

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [BitConverter](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)