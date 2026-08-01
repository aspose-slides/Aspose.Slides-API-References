---
title: CopyTo()
second_title: Aspose.Slides voor C++ API-referentie
description: Kopieert lijstonderdelen naar bestaande array-elementen.
type: docs
weight: 209
url: /nl/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) methode


Kopieert lijstonderdelen naar bestaande array-elementen.

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | Doel-array. |
| arrayIndex | int | Beginindex van de doel-array. |

## List::CopyTo(const System::ArrayPtr\<T\>\&) methode


Kopieert alle elementen naar bestaande array-elementen.

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) om elementen in te kopiëren. |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) methode


Kopieert elementen beginnend bij de opgegeven index naar bestaande array-elementen.

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Een 0-gebaseerde index van het element in de lijst die door het huidige object wordt gerepresenteerd, waarvandaan gekopieerd moet worden |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) om elementen in te kopiëren. |
| arrayIndex | int | Beginpositie in de doel-array. |
| count | int | Aantal elementen om te kopiëren. |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [List](../)
* Naamruimte [System::Collections::Generic](../../)
* Bibliotheek [Aspose.Slides](../../../)