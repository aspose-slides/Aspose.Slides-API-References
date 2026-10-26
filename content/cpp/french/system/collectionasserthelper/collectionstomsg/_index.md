---
title: CollectionsToMsg()
second_title: Référence API Aspose.Slides pour C++
description: Sérialise deux collections pour la représentation du message.
type: docs
weight: 53
url: /fr/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) méthode

Sérialise deux collections pour la représentation du message.

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Type d'élément de collection attendu. |
| T2 | Type d'élément de collection réel. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)\& | Une chaîne personnalisée qui est insérée avant la valeur attendue dans le message résultant |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Collection attendue. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Collection réelle. |

### Valeur de retour

Message convivial sur le contenu des collections.

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [CollectionAssertHelper](../)
* Espace de noms [System](../../)
* Library [Aspose.Slides](../../../)