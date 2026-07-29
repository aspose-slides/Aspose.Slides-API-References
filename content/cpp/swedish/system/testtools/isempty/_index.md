---
title: IsEmpty()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar om strängen är tom.
type: docs
weight: 14
url: /sv/system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) metod


Kontrollerar om strängen är tom.

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) för att kontrollera om den är tom. |

### Returvärde

Sant om strängen är tom (null-length), annars falskt.

## TestTools::IsEmpty(const SharedPtr\<T\>\&) metod


Kontrollerar om samlingen är tom.

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Samlingstyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Samling att kontrollera. |

### Returvärde

Sant om samlingen har noll element, annars falskt.

## Se också

* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../../string/)
* Struktur [TestTools](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)