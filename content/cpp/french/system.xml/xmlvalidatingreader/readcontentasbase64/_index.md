---
title: ReadContentAsBase64()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lit le contenu et renvoie les octets binaires décodés en Base64.
type: docs
weight: 573
url: /fr/system.xml/xmlvalidatingreader/readcontentasbase64/
---
## XmlValidatingReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method


Lit le contenu et renvoie les octets binaires décodés en Base64.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tampon dans lequel copier le texte résultant. Cette valeur ne peut pas être **nullptr**. |
| index | **int32_t** | Le décalage dans le tampon où commencer à copier le résultat. |
| count | **int32_t** | Le nombre maximum d'octets à copier dans le tampon. Le nombre réel d'octets copiés est renvoyé par cette méthode. |

### Valeur de retour

Le nombre d'octets écrits dans le tampon.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [XmlValidatingReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)