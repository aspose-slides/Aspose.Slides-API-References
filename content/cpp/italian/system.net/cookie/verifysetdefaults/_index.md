---
title: VerifySetDefaults()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica e imposta i valori predefiniti dell'attributo.
type: docs
weight: 482
url: /it/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) metodo

Verifica e imposta i valori predefiniti degli attributi.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | La specifica del cookie. |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'istanza della classe Uri che viene usata per inizializzare i campi interni. |
| isLocalDomain | **bool** | Un valore che indica se il cookie è inserito nel dominio locale. |
| localDomain | [String](../../../system/string/) | Un nome di dominio locale. |
| setDefault | **bool** | Un valore che indica se gli attributi del cookie devono essere inizializzati usando i loro valori predefiniti. |
| shouldThrow | **bool** | Un valore che indica se deve essere sollevata un'eccezione quando i valori specificati non sono validi. |

### Valore restituito

Vero quando tutti i valori sono validi, altrimenti falso.

## Vedi anche

* Enum [CookieVariant](../../cookievariant/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [Cookie](../)
* Spazio dei nomi [System::Net](../../)
* Libreria [Aspose.Slides](../../../)