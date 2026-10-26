---
title: BaseDictionary()
second_title: Aspose.Slides C++ API referencia
description: Üres adatstruktúrát hoz létre.
type: docs
weight: 14
url: /hu/system.collections.generic/basedictionary/basedictionary/
---
## BaseDictionary::BaseDictionary() konstruktor


Üres adatstruktúrát hoz létre.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary()
```

## BaseDictionary::BaseDictionary(int, const Args\&...) konstruktor


Továbbító konstruktor az argumentumok alapértelmezett térkép-konstruktorba történő továbbításához.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(int, const Args &... args)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Args | Az átküldendő argumentumok típusai a térképhez. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| args | int | Az alapértelmezett térképnek átadandó argumentumok. |

## BaseDictionary::BaseDictionary(BaseType *, const Args\&...) konstruktor


Másoló konstruktor.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src, const Args &... args)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Args | A térkép-konstruktor argumentumainak típusai. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) amiből az adatokat másoljuk. |
| args | const Args\&... | Az alapértelmezett térkép-konstruktorba átadandó argumentumok. |

## BaseDictionary::BaseDictionary(BaseType *) konstruktor


Másoló konstruktor.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) amiből az adatokat másoljuk. |

## Lásd még

* Típusdefiníció [BaseType](../basetype/)
* Osztály [BaseDictionary](../)
* Névterület [System::Collections::Generic](../../)
* Könyvtár [Aspose.Slides](../../../)