---
title: get_font_bytes method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ifontsmanager/get_font_bytes/
weight: 30
---
## get_font_bytes(self, font_data, font_style) {#ifontdata-fontstyletype}
Récupère le tableau d’octets représentant les données de police pour un style de police et des données de police spécifiés.

### Retour

Un tableau d’octets contenant les données de police pour le style de police spécifié. Si les données de police ou le style ne sont pas trouvés, retourne None.



```python
def get_font_bytes(self, font_data, font_style):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| font_data | [`IFontData`](/slides/python-net/fr/aspose.slides/ifontdata) | L’objet contenant les données de police avec les informations sur la police [`IFontData`](/slides/python-net/fr/aspose.slides/ifontdata). |
| font_style | [`FontStyleType`](/slides/python-net/fr/aspose.slides/fontstyletype) | Le style de la police dont les données doivent être récupérées [`FontStyleType`](/slides/python-net/fr/aspose.slides/fontstyletype). |



### Voir aussi
* énumération [`FontStyleType`](/slides/python-net/fr/aspose.slides/fontstyletype)
* classe [`IFontData`](/slides/python-net/fr/aspose.slides/ifontdata)
* classe [`IFontsManager`](/slides/python-net/fr/aspose.slides/ifontsmanager)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)