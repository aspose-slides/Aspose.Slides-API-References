---
title: VerifySetDefaults()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft und setzt die Standardwerte der Attribute.
type: docs
weight: 482
url: /de/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) Methode

Überprüft und setzt die Standardwerte der Attribute.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | Die Spezifikation des Cookies. |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Die Uri-Klasseninstanz, die zum Initialisieren der internen Felder verwendet wird. |
| isLocalDomain | **bool** | Ein Wert, der angibt, ob das Cookie in die lokale Domäne eingefügt wird. |
| localDomain | [String](../../../system/string/) | Ein lokaler Domänenname. |
| setDefault | **bool** | Ein Wert, der angibt, ob die Attribute des Cookies mit ihren Standardwerten initialisiert werden müssen. |
| shouldThrow | **bool** | Ein Wert, der angibt, ob eine Ausnahme ausgelöst werden soll, wenn die angegebenen Werte ungültig sind. |

### Rückgabewert

Wahr, wenn alle Werte gültig sind, andernfalls falsch.

## Siehe auch

* Enum [CookieVariant](../../cookievariant/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [Cookie](../)
* Namensraum [System::Net](../../)
* Bibliothek [Aspose.Slides](../../../)