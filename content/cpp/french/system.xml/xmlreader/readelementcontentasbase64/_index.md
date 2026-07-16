---
title: ReadElementContentAsBase64()
second_title: Référence API Aspose.Slides pour C++
description: Lit l'élément et décode le contenu Base64.
type: docs
weight: 768
url: /fr/system.xml/xmlreader/readelementcontentasbase64/
---
## XmlReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) méthode

Lit l'élément et décode le contenu **Base64**.

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tampon dans lequel copier le texte résultant. Cette valeur ne peut pas être **nullptr**. |
| index | **int32_t** | Le décalage dans le tampon où commencer à copier le résultat. |
| count | **int32_t** | Le nombre maximal d'octets à copier dans le tampon. Le nombre réel d'octets copiés est renvoyé par cette méthode. |

### Valeur de retour

Le nombre d'octets écrits dans le tampon.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [XmlReader](../)
* Espace de noms [System::Xml](../../)
* Library [Aspose.Slides](../../../)