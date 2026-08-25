---
title: Fonts
second_title: Référence de l'API Java Aspose.Sildes pour PHP
description: 
type: docs

url: /fr/aspose.slides/fonts/
---
## Fonts classe

 Collection de polices.
 
### getComplexScriptFont {#getComplexScriptFont}

| Nom | Description |
| --- | --- |
| getComplexScriptFont () | Renvoie ou définit la police de script complexe. Lecture/écriture IFontData. |

**Renvoie:**
[FontData](../fontdata)


---


### getEastAsianFont {#getEastAsianFont}

| Nom | Description |
| --- | --- |
| getEastAsianFont () | Renvoie ou définit la police d'Asie de l'Est. Lecture/écriture IFontData. |

**Renvoie:**
[FontData](../fontdata)


---


### getLatinFont {#getLatinFont}

| Nom | Description |
| --- | --- |
| getLatinFont () | Renvoie ou définit la police latine. Lecture/écriture IFontData. |

**Renvoie:**
[FontData](../fontdata)


---


### getScriptFont {#getScriptFont}

| Nom | Description |
| --- | --- |
| getScriptFont (String) | Obtient le nom de la police associé à une balise de script spécifique du thème de la présentation. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| script | String | Le code de script BCP-47 (par ex., « Latn », « Cyrl », « Jpan ») utilisé pour identifier un système d'écriture. |

**Renvoie:**
String


---


### getScriptFontMap {#getScriptFontMap}

| Nom | Description |
| --- | --- |
| getScriptFontMap () | Renvoie un dictionnaire de toutes les définitions de polices de script dans la présentation. |

**Renvoie:**
Dictionary


---


### removeScriptFont {#removeScriptFont}

| Nom | Description |
| --- | --- |
| removeScriptFont (String) | Supprime le paramètre de police associé à une balise de script spécifique de la collection de polices du thème. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| script | String | Le code de script BCP-47 dont le paramètre de police doit être supprimé. |

**Renvoie:**
void


---


### setComplexScriptFont {#setComplexScriptFont}

| Nom | Description |
| --- | --- |
| setComplexScriptFont ([FontData](../fontdata)) | Renvoie ou définit la police de script complexe. Lecture/écriture IFontData. |

**Renvoie:**
void


---


### setEastAsianFont {#setEastAsianFont}

| Nom | Description |
| --- | --- |
| setEastAsianFont ([FontData](../fontdata)) | Renvoie ou définit la police d'Asie de l'Est. Lecture/écriture IFontData. |

**Renvoie:**
void


---


### setLatinFont {#setLatinFont}

| Nom | Description |
| --- | --- |
| setLatinFont ([FontData](../fontdata)) | Renvoie ou définit la police latine. Lecture/écriture IFontData. |

**Renvoie:**
void


---


### setScriptFont {#setScriptFont}

| Nom | Description |
| --- | --- |
| setScriptFont (String, String) | Attribue un nom de police à une balise de script spécifique, ce qui définit comment le texte de ce script sera rendu dans la présentation. |

**Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| script | String | Le code de script BCP-47 (par ex., « Arab », « Hebr », « Hans ») identifiant le système d'écriture. |
| fontName | String | Le nom de la police à attribuer au script spécifié. |

**Renvoie:**
void


---