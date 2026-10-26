---
title: TrimStart()
second_title: Aspose.Slides C++ API referencia
description: Eltávolítja az összes szóköz karaktert a karakterlánc elejéről.
type: docs
weight: 690
url: /hu/system/string/trimstart/
---
## String::TrimStart() const metódus

Eltávolítja az összes szóköz karaktert a karakterlánc elejéről.

```cpp
String System::String::TrimStart() const
```

### Visszatérési érték

[String](../) nincsenek szóközök a kezdetén.

## String::TrimStart(char_t) const metódus

Eltávolítja a megadott karakter összes előfordulását a karakterlánc elejéről.

```cpp
String System::String::TrimStart(char_t ch) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ch | char_t | Az eltávolítandó szimbólum. |

### Visszatérési érték

Az eltávolítás eredménye.

## String::TrimStart(const String\&) const metódus

Eltávolítja a megadott karakterek összes előfordulását a karakterlánc elejéről.

```cpp
String System::String::TrimStart(const String &anyOf) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) karakterek eltávolításához. |

### Visszatérési érték

[String](../) az eltávolított karakterek nélkül.

## String::TrimStart(const ArrayPtr\<char_t\>\&) const metódus

Eltávolítja a megadott karakterek összes előfordulását a karakterlánc elejéről.

```cpp
String System::String::TrimStart(const ArrayPtr<char_t> &anyOf) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) karakterek eltávolításához. |

### Visszatérési érték

[String](../) az eltávolított karakterek nélkül.

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Osztály [String](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)