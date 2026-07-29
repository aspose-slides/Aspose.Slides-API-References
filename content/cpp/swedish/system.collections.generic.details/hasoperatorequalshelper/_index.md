---
title: HasOperatorEqualsHelper()
second_title: Aspose.Slides för C++ API-referens
description: Hjälpfunktion för att avgöra om en specifik klass har operator ==.
type: docs
weight: 235
url: /sv/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) funktion


Hjälpfunktion för att avgöra om en specifik klass har operator ==.

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ att kontrollera. |
| Dummy | Dummy-argument för SFINAE-magi. |

### Returvärde

Värde av std::true_type om operator == är närvarande och falskt annars.

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) funktion


Hjälpfunktion för att avgöra om en specifik klass har operator ==.

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```


### Returvärde

Värde av std::true_type om operator == är närvarande och falskt annars.

## Se även

* Namnrymd [System::Collections::Generic::Details](../)
* Bibliotek [Aspose.Slides](../../)