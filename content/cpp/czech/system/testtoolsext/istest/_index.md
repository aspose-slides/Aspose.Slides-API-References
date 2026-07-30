---
title: IsTest()
second_title: Aspose.Slides pro C++ – dokumentace API
description: Kontroluje, zda testovací metoda existuje.
type: docs
weight: 1
url: /cs/system/testtoolsext/istest/
---
## TestToolsExt::IsTest(const char *, const char *, const char *) metoda

Kontroluje, zda testovací metoda existuje.

```cpp
static bool System::TestToolsExt::IsTest(const char *name_space, const char *class_name, const char *method_name)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name_space | const char * | Jmenný prostor, ve kterém se hledá. |
| class_name | const char * | Třída, která se hledá. |
| method_name | const char * | Metoda, která se hledá. |

### Návratová hodnota

True pokud je testovací metoda registrována, false jinak.

## TestToolsExt::IsTest(const char *, const char *) metoda

Kontroluje, zda testovací metoda existuje.

```cpp
static bool System::TestToolsExt::IsTest(const char *class_name, const char *method_name)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| class_name | const char * | Třída, která se hledá. |
| method_name | const char * | Metoda, která se hledá. |

### Návratová hodnota

True pokud je testovací metoda registrována, false jinak.

## Viz také

* Struktura [TestToolsExt](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)