---
title: Format()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une représentation sous forme de chaîne d'une valeur représentée par l'objet actuel en utilisant le format spécifié.
type: docs
weight: 1
url: /fr/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) méthode

Renvoie une représentation sous forme de chaîne d'une valeur représentée par l'objet actuel en utilisant le format spécifié.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| format | [System::String](../../string/) | The string format |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | The object to be formatted |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | The object providing the formatting information |

### Valeur de retour

La représentation sous forme de chaîne de **arg** formatée selon le format spécifié par **format** et **formatProvider**

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Object](../../object/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [ICustomFormatter](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)