---
title: WriteState
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie l'état du XmlWriter.
type: docs
weight: 755
url: /fr/system.xml/writestate/
---
## WriteState enum

Spécifie l'état du [XmlWriter](../xmlwriter/).

```cpp
enum class WriteState
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Start | 0 | Indique que la méthode XmlWriter::Write n'a pas encore été appelée. |
| Prolog | 1 | Indique que le prologue est en cours d'écriture. |
| Element | 2 | Indique qu'une balise de démarrage d'élément est en cours d'écriture. |
| Attribute | 3 | Indique qu'une valeur d'attribut est en cours d'écriture. |
| Content | 4 | Indique que le contenu de l'élément est en cours d'écriture. |
| Closed | 5 | Indique que la méthode [XmlWriter::Close](../xmlwriter/close/) a été appelée. |
| Error | 6 | Une exception a été levée, ce qui a laissé le [XmlWriter](../xmlwriter/) dans un état invalide. Vous pouvez appeler la méthode [XmlWriter::Close](../xmlwriter/close/) pour placer le [XmlWriter](../xmlwriter/) dans l'état [WriteState::Closed](./). Tout autre appel de méthode [XmlWriter](../xmlwriter/) entraîne une InvalidOperationException. |

## See Also

* Espace de noms [System::Xml](../)
* Bibliothèque [Aspose.Slides](../../)