---
title: VerifySetDefaults()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Weryfikuje i ustawia domyślne wartości atrybutu.
type: docs
weight: 482
url: /pl/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) metoda


Weryfikuje i ustawia domyślne wartości atrybutu.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | Specyfikacja ciasteczka. |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Instancja klasy Uri, która jest używana do inicjalizacji pól wewnętrznych. |
| isLocalDomain | **bool** | Wartość określająca, czy ciasteczko jest przesyłane do domeny lokalnej. |
| localDomain | [String](../../../system/string/) | Nazwa lokalnej domeny. |
| setDefault | **bool** | Wartość określająca, czy atrybuty ciasteczka muszą być inicjalizowane przy użyciu ich domyślnych wartości. |
| shouldThrow | **bool** | Wartość określająca, czy należy rzucić wyjątek, gdy podane wartości są nieprawidłowe. |

### Wartość zwracana

True, gdy wszystkie wartości są prawidłowe, w przeciwnym razie false.

## Zobacz także

* Wyliczenie [CookieVariant](../../cookievariant/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Uri](../../../system/uri/)
* Klasa [String](../../../system/string/)
* Klasa [Cookie](../)
* Przestrzeń nazw [System::Net](../../)
* Biblioteka [Aspose.Slides](../../../)