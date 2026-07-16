---
title: Add()
second_title: Référence API Aspose.Slides pour C++
description: Atomise la chaîne spécifiée et l'ajoute à la NameTable.
type: docs
weight: 14
url: /fr/system.xml/nametable/add/
---
## NameTable::Add(const String\&) méthode


Atomise la chaîne spécifiée et l'ajoute au [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| key | const [String](../../../system/string/)\& | La chaîne à ajouter. |

### Valeur de retour

La chaîne atomisée ou la chaîne existante si elle existe déjà dans le [NameTable](../).

## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) méthode


Atomise la chaîne spécifiée et l'ajoute au [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Le tableau de caractères contenant la chaîne à ajouter. |
| start | **int32_t** | L'index de base zéro dans le tableau spécifiant le premier caractère de la chaîne. |
| len | **int32_t** | Le nombre de caractères dans la chaîne. |

### Valeur de retour

La chaîne atomisée ou la chaîne existante si elle existe déjà dans le [NameTable](../). Si **len** est zéro, [String::Empty](../../../system/string/empty/) est renvoyé.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [NameTable](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)