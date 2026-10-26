---
title: FontSubstRule
second_title: Aspose.Sildes pour PHP via la référence de l'API Java
description: 
type: docs

url: /fr/aspose.slides/fontsubstrule/
---
## FontSubstRule classe

Représente les informations de substitution de police

### FontSubstRule {#FontSubstRule}

| Name | Description |
| --- | --- |
| FontSubstRule([FontData](../fontdata), [FontData](../fontdata)) | Crée une nouvelle instance. |

**Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| sourceFont | [FontData](../fontdata) | Police source. |
| destFont | [FontData](../fontdata) | Police de destination. |

**Retour:**
FontSubstRule


---

### FontSubstRule {#FontSubstRule}

| Name | Description |
| --- | --- |
| FontSubstRule([FontData](../fontdata), [FontData](../fontdata), int) | Crée une nouvelle instance. |

**Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| sourceFont | [FontData](../fontdata) | Police source. |
| destFont | [FontData](../fontdata) | Police de destination. |
| fontSubstRule | int | Règle de substitution de police. |

**Retour:**
FontSubstRule


---

### getDestFont {#getDestFont}

| Name | Description |
| --- | --- |
| getDestFont () | Police à utiliser pour la substitution. Lecture seule IFontData. |

**Retour:**
[FontData](../fontdata)


---

### getReplaceFontCondition {#getReplaceFontCondition}

| Name | Description |
| --- | --- |
| getReplaceFontCondition () | Règle à appliquer pour la substitution. Lecture seule FontSubstCondition. |

**Retour:**
int


---

### getSourceFont {#getSourceFont}

| Name | Description |
| --- | --- |
| getSourceFont () | Police à substituer. Lecture seule IFontData. |

**Retour:**
[FontData](../fontdata)