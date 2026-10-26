---
title: TrimEnd()
second_title: Aspose.Slides C++ API referencia
description: Eltávolítja az összes szóköz karaktert a karakterlánc végéről.
type: docs
weight: 703
url: /hu/system/string/trimend/
---
## String::TrimEnd() const metódus


Eltávolítja az összes szóköz karaktert a karakterlánc végéről.

```cpp
String System::String::TrimEnd() const
```


### Visszatérési érték

[String](../) nincsenek szóközök az elején.

## String::TrimEnd(char_t) const metódus


Eltávolítja a megadott karakter összes előfordulását a karakterlánc végéről.

```cpp
String System::String::TrimEnd(char_t ch) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ch | char_t | Eltávolítandó szimbólum. |

### Visszatérési érték

Az eltávolítás eredménye.

## String::TrimEnd(const String\&) const metódus


Eltávolítja a megadott karakterek összes előfordulását a karakterlánc végéről.

```cpp
String System::String::TrimEnd(const String &anyOf) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) karakterek eltávolításához. |

### Visszatérési érték

[String](../) eltávolított karakterek nélkül.

## String::TrimEnd(const ArrayPtr\<char_t\>\&) const metódus


Eltávolítja a megadott karakterek összes előfordulását a karakterlánc végéről.

```cpp
String System::String::TrimEnd(const ArrayPtr<char_t> &anyOf) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) karakterek eltávolításához. |

### Visszatérési érték

[String](../) eltávolított karakterek nélkül.

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Osztály [String](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)