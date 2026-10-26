---
title: Trim()
second_title: Aspose.Slides C++ API hivatkozás
description: Eltávolítja az összes szóköz karaktert a karakterlánc elejéről és végéről.
type: docs
weight: 677
url: /hu/system/string/trim/
---
## String::Trim() const metódus


Eltávolítja az összes szóköz karaktert a karakterlánc elejéről és végéről.

```cpp
String System::String::Trim() const
```


### Visszatérési érték

[String](../) szóközök nélkül a kezdeten vagy a végén.

## String::Trim(char_t) const metódus


Eltávolítja a megadott karakter összes előfordulását a karakterlánc elejéről és végéről.

```cpp
String System::String::Trim(char_t ch) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ch | char_t | Eltávolítandó szimbólum. |

### Visszatérési érték

Eltávolítási eredmény.

## String::Trim(const String\&) const metódus


Eltávolítja a megadott karakterek összes előfordulását a karakterlánc elejéről és végéről.

```cpp
String System::String::Trim(const String &anyOf) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) a eltávolítandó karakterek. |

### Visszatérési érték

[String](../) a eltávolított karakterek nélkül.

## String::Trim(const ArrayPtr\<char_t\>\&) const metódus


Eltávolítja a megadott karakterek összes előfordulását a karakterlánc elejéről és végéről.

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) a eltávolítandó karakterek. |

### Visszatérési érték

[String](../) a eltávolított karakterek nélkül.

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Osztály [String](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)