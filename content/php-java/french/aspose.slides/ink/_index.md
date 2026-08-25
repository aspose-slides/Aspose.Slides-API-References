---
title: Ink
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/ink/
---
## Classe Ink

 Représente un objet d'encre sur une diapositive.
 
### getInkEffectImages {#getInkEffectImages}

| Nom | Description |
| --- | --- |
| getInkEffectImages () | Obtient la collection d'images personnalisées utilisées pour simuler des effets visuels pour les pinceaux d'encre. Ces images sont utilisées lors du rendu de l'encre avec des valeurs spécifiques de InkEffectType, telles que Galaxy, Rainbow, etc. En fournissant vos propres images, vous pouvez contrôler l'apparence de chaque effet d'encre. Cette propriété permet de remplacer les textures d'effet d'encre par défaut par des textures définies par l'utilisateur, ce qui est particulièrement utile lorsque les ressources par défaut sont restreintes par des licences ou indisponibles à l'exécution. Chaque entrée du dictionnaire doit associer une valeur InkEffectType à un objet IImage correspondant (par exemple, Bitmap, ou une interface d'image Aspose). |

 **Retour:**  
Dictionary


---


### getTraces {#getTraces}

| Nom | Description |
| --- | --- |
| getTraces () | Obtient toutes les traces contenues dans l'élément IInk IInkTrace. Lecture seule. |

 **Retour:**  
[InkTrace](../inktrace)


---