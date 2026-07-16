---
title: ReadChars()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lit le contenu texte d'un élément dans un tampon de caractères. Cette méthode est conçue pour lire de grands flux de texte incorporé en l'appelant successivement.
type: docs
weight: 755
url: /fr/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) méthode

Lit le contenu texte d'un élément dans un tampon de caractères. Cette méthode est conçue pour lire de grands flux de texte incorporé en l'appelant successivement.

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Le tableau de caractères qui sert de tampon où le contenu texte est écrit. |
| index | **int32_t** | La position dans **buffer** où la méthode peut commencer à écrire le contenu texte. |
| count | **int32_t** | Le nombre de caractères à écrire dans **buffer**. |

### Valeur de retour

Le nombre de caractères lus. Cela peut être 0 si le lecteur n'est pas positionné sur un élément ou s'il n'y a plus de contenu texte à retourner dans le contexte actuel.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)