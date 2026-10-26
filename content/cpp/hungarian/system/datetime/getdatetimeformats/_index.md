---
title: GetDateTimeFormats()
second_title: Aspose.Slides C++ API referencia
description: Visszaad egy karakterláncok tömbjét, ahol minden elem a jelenlegi objektum string ábrázolása, amelyet az egyik szabványos dátum- és időformátum specifikátorral formázott.
type: docs
weight: 547
url: /hu/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const metódus


Visszaad egy karakterláncok tömbjét, ahol minden elem a jelenlegi objektum string ábrázolása, amelyet az egyik szabványos dátum- és időformátum specifikátorral formázott.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```

## DateTime::GetDateTimeFormats(char_t) const metódus


Visszaad egy karakterláncok tömbjét, ahol minden elem a jelenlegi objektum string ábrázolása, amelyet a megadott szabványos dátum- és időformátum specifikátorral formázott.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | char_t | Szabványos dátum- és időformátum specifikátor. |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const metódus


Visszaad egy karakterláncok tömbjét, ahol minden elem a jelenlegi objektum string ábrázolása, amelyet az egyik szabványos dátum- és időformátum specifikátorral, valamint a megadott formátum szolgáltatóval formázott.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formátum szolgáltató. |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const metódus


Visszaad egy karakterláncok tömbjét, ahol minden elem a jelenlegi objektum string ábrázolása, amelyet a megadott szabványos dátum- és időformátum specifikátorral és formátum szolgáltatóval formázott.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | char_t | Szabványos dátum- és időformátum specifikátor. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formátum szolgáltató. |

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Osztály [DateTime](../)
* Osztály [IFormatProvider](../../iformatprovider/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)