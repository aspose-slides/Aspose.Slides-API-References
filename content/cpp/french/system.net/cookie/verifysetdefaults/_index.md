---
title: VerifySetDefaults()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Vérifie et définit les valeurs par défaut des attributs.
type: docs
weight: 482
url: /fr/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) méthode

Vérifie et définit les valeurs par défaut des attributs.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | Spécification du cookie. |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'instance de la classe Uri utilisée pour initialiser les champs internes. |
| isLocalDomain | **bool** | Une valeur indiquant si le cookie est placé dans le domaine local. |
| localDomain | [String](../../../system/string/) | Un nom de domaine local. |
| setDefault | **bool** | Une valeur indiquant si les attributs du cookie doivent être initialisés avec leurs valeurs par défaut. |
| shouldThrow | **bool** | Une valeur indiquant si une exception doit être levée lorsque les valeurs spécifiées sont invalides. |

### Valeur de retour

Vrai lorsque toutes les valeurs sont valides, sinon faux.

## Voir aussi

* Énumération [CookieVariant](../../cookievariant/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [Cookie](../)
* Espace de noms [System::Net](../../)
* Bibliothèque [Aspose.Slides](../../../)