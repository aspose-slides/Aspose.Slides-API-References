---
title: VerifySetDefaults()
second_title: Aspose.Slides a C++ API referencia
description: Ellenőrzi és beállítja az alapértelmezett attribútum értékeit.
type: docs
weight: 482
url: /hu/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) metódus

Ellenőrzi és beállítja az alapértelmezett attribútumok értékeit.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | A süti specifikációja. |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | A Uri-osztály példánya, amelyet a belső mezők inicializálásához használnak. |
| isLocalDomain | **bool** | Egy érték, amely azt jelzi, hogy a süti a helyi tartományba került-e. |
| localDomain | [String](../../../system/string/) | Egy helyi tartománynév. |
| setDefault | **bool** | Egy érték, amely azt jelzi, hogy a süti attribútumait az alapértelmezett értékekkel kell-e inicializálni. |
| shouldThrow | **bool** | Egy érték, amely azt jelzi, hogy kivételt kell-e dobni, ha a megadott értékek érvénytelenek. |

### Visszatérési érték

Igaz, ha minden érték érvényes, egyébként hamis.

## Lásd még

* Enum [CookieVariant](../../cookievariant/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Uri](../../../system/uri/)
* Osztály [String](../../../system/string/)
* Osztály [Cookie](../)
* Névtér [System::Net](../../)
* Library [Aspose.Slides](../../../)