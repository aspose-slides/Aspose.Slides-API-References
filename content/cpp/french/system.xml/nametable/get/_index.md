---
title: Get()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie la chaîne atomisée avec la valeur spécifiée.
type: docs
weight: 27
url: /fr/system.xml/nametable/get/
---
## NameTable::Get(const String\&) méthode

Renvoie la chaîne atomisée contenant la valeur spécifiée.

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Le nom à rechercher. |

### Valeur de retour

L'objet chaîne atomisée ou **nullptr** si la chaîne n'a pas encore été atomisée.

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) méthode

Renvoie la chaîne atomisée contenant les mêmes caractères que la plage spécifiée de caractères dans le tableau fourni.

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Le tableau de caractères contenant le nom à rechercher. |
| start | **int32_t** | L'index de base zéro dans le tableau spécifiant le premier caractère du nom. |
| len | **int32_t** | Le nombre de caractères dans le nom. |

### Valeur de retour

La chaîne atomisée ou **nullptr** si la chaîne n'a pas encore été atomisée. Si **len** est zéro, [String::Empty](../../../system/string/empty/) est renvoyé.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [NameTable](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)