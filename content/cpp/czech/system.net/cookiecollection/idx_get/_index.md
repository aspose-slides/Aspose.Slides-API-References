---
title: idx_get()
second_title: Aspose.Slides pro C++ API Reference
description: Vrátí cookie ze sbírky cookie na zadaném indexu.
type: docs
weight: 40
url: /cs/system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) metoda

Vrátí cookie ze sbírky cookie na zadaném indexu.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index cookie, který má být vrácen. |

### Návratová hodnota

Cookie na zadaném indexu.

## CookieCollection::idx_get(String) metoda

Vrátí cookie ze sbírky cookie podle zadaného názvu.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název cookie, který má být vrácen. |

### Návratová hodnota

Cookie ze sbírky cookie podle zadaného názvu, pokud je nalezena, jinak nullptr.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Cookie](../../cookie/)
* Třída [CookieCollection](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Net](../../)
* Library [Aspose.Slides](../../../)