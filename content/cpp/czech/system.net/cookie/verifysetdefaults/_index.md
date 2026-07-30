---
title: VerifySetDefaults()
second_title: Aspose.Slides pro C++ API Reference
description: Ověří a nastaví výchozí hodnoty atributů.
type: docs
weight: 482
url: /cs/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) metoda


Ověří a nastaví výchozí hodnoty atributů.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | Specifikace souboru cookie. |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Instance třídy Uri, která se používá k inicializaci vnitřních polí. |
| isLocalDomain | **bool** | Hodnota, která určuje, zda je soubor cookie umístěn do místní domény. |
| localDomain | [String](../../../system/string/) | Název místní domény. |
| setDefault | **bool** | Hodnota, která určuje, zda mají být atributy souboru cookie inicializovány pomocí jejich výchozích hodnot. |
| shouldThrow | **bool** | Hodnota, která určuje, zda má být vyvolána výjimka, když jsou zadané hodnoty neplatné. |

### Návratová hodnota

True, pokud jsou všechny hodnoty platné, jinak false.

## Viz také

* Enum [CookieVariant](../../cookievariant/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Uri](../../../system/uri/)
* Třída [String](../../../system/string/)
* Třída [Cookie](../)
* Jmenný prostor [System::Net](../../)
* Library [Aspose.Slides](../../../)