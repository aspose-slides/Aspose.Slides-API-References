---
title: ReadValueChunk()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lit de grands flux de texte intégrés dans un document XML.
type: docs
weight: 807
url: /fr/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) méthode

Lit de grands flux de texte intégrés dans un document XML.

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Le tableau de caractères qui sert de tampon dans lequel le contenu texte est écrit. Cette valeur ne peut pas être **nullptr**. |
| index | **int32_t** | Le décalage dans le tampon où le [XmlReader](../) peut commencer à copier les résultats. |
| count | **int32_t** | Le nombre maximal de caractères à copier dans le tampon. Le nombre réel de caractères copiés est renvoyé par cette méthode. |

### Valeur de retour

Le nombre de caractères lus dans le tampon. La valeur zéro est renvoyée lorsqu'il n'y a plus de contenu texte.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [XmlReader](../)
* Espace de noms [System::Xml](../../)
* Library [Aspose.Slides](../../../)