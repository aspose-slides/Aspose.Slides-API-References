---
title: ISensitivityLabel
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the sensitivity label from Microsoft Purview Information Protection.
type: docs
url: /fr/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Représente l'étiquette de sensibilité de Microsoft Purview Information Protection.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getId()](#getId--) | Renvoie ou définit l'identifiant de l'étiquette de sensibilité. |
| [setId(String value)](#setId-java.lang.String-) | Renvoie ou définit l'identifiant de l'étiquette de sensibilité. |
| [getSiteId()](#getSiteId--) | Renvoie ou définit l'identifiant du site Azure Active Directory (Azure AD) correspondant à la stratégie d'étiquette de sensibilité qui décrit l'étiquette de sensibilité. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Renvoie ou définit l'identifiant du site Azure Active Directory (Azure AD) correspondant à la stratégie d'étiquette de sensibilité qui décrit l'étiquette de sensibilité. |
| [isEnabled()](#isEnabled--) | Indique si l'étiquette de sensibilité est activée. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Indique si l'étiquette de sensibilité est activée. |
| [isRemoved()](#isRemoved--) | Indique si l'étiquette de sensibilité a été supprimée. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Indique si l'étiquette de sensibilité a été supprimée. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Renvoie ou définit la méthode d'attribution pour l'étiquette de sensibilité. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Renvoie ou définit la méthode d'attribution pour l'étiquette de sensibilité. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Renvoie la liste des types de marquage de contenu qui doivent être appliqués à un fichier. |
### getId() {#getId--}
```
public abstract String getId()
```

Renvoie ou définit l'identifiant de l'étiquette de sensibilité. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

Renvoie ou définit l'identifiant de l'étiquette de sensibilité. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```

Renvoie ou définit l'identifiant du site Azure Active Directory (Azure AD) correspondant à la stratégie d'étiquette de sensibilité qui décrit l'étiquette de sensibilité. Lecture/écriture java.util.UUID.

**Renvoie :**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```

Renvoie ou définit l'identifiant du site Azure Active Directory (Azure AD) correspondant à la stratégie d'étiquette de sensibilité qui décrit l'étiquette de sensibilité. Lecture/écriture java.util.UUID.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```

Indique si l'étiquette de sensibilité est activée.

**Renvoie :**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```

Indique si l'étiquette de sensibilité est activée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```

Indique si l'étiquette de sensibilité a été supprimée.

**Renvoie :**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```

Indique si l'étiquette de sensibilité a été supprimée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```

Renvoie ou définit la méthode d'attribution pour l'étiquette de sensibilité. Lecture/écriture [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Renvoie :**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```

Renvoie ou définit la méthode d'attribution pour l'étiquette de sensibilité. Lecture/écriture [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

Renvoie la liste des types de marquage de contenu qui doivent être appliqués à un fichier.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Une liste de types de contenu [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)