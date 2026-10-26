---
title: AppendFormat()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une chaîne formatée au builder.
type: docs
weight: 131
url: /fr/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String\&, const TArgs\&...) méthode


Ajoute une chaîne formatée au builder.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TArgs | Type des arguments. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Chaîne de format. |
| args | const TArgs\&... | Arguments à insérer aux positions de la chaîne de format. |

### Valeur de retour

Ce pointeur.

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>\&, const String\&, const TArgs\&...) méthode


Ajoute une chaîne formatée au builder.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TArgs | Type des arguments. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)\<[IFormatProvider](../../../system/iformatprovider/)\>\& | Fournisseur de format ; ignoré. |
| format | const [String](../../../system/string/)\& | Chaîne de format. |
| args | const TArgs\&... | Arguments à insérer aux positions de la chaîne de format. |

### Valeur de retour

Ce pointeur.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [StringBuilder](../)
* Classe [String](../../../system/string/)
* Classe [IFormatProvider](../../../system/iformatprovider/)
* Espace de noms [System::Text](../../)
* Bibliothèque [Aspose.Slides](../../../)