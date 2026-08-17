---
title: ISensitivityLabel
second_title: Aspose.Slides for Java API Reference
description: Représente le label de sensibilité de Microsoft Purview Information Protection.
type: docs
url: /fr/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Représente le label de sensibilité de Microsoft Purview Information Protection.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getId()](#getId--) | Renvoie ou définit l'ID du label de sensibilité. |
| [setId(String value)](#setId-java.lang.String-) | Renvoie ou définit l'ID du label de sensibilité. |
| [getSiteId()](#getSiteId--) | Renvoie ou définit l'identifiant du site Azure Active Directory (Azure AD) correspondant à la stratégie de label de sensibilité qui décrit le label de sensibilité. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Renvoie ou définit l'identifiant du site Azure Active Directory (Azure AD) correspondant à la stratégie de label de sensibilité qui décrit le label de sensibilité. |
| [isEnabled()](#isEnabled--) | Indique si le label de sensibilité est activé. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Indique si le label de sensibilité est activé. |
| [isRemoved()](#isRemoved--) | Indique si le label de sensibilité a été supprimé. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Indique si le label de sensibilité a été supprimé. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Renvoie ou définit la méthode d'affectation du label de sensibilité. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Renvoie ou définit la méthode d'affectation du label de sensibilité. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Renvoie la liste des types de marquage de contenu qui doivent être appliqués à un fichier. |
### getId() {#getId--}
```
public abstract String getId()
```

Renvoie ou définit l'ID du label de sensibilité. Lecture/écriture String.

**Returns:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

Renvoie ou définit l'ID du label de sensibilité. Lecture/écriture String.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```

Renvoie ou définit l'identifiant du site Azure Active Directory (Azure AD) correspondant à la stratégie de label de sensibilité qui décrit le label de sensibilité. Lecture/écriture java.util.UUID.

**Returns:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```

Renvoie ou définit l'identifiant du site Azure Active Directory (Azure AD) correspondant à la stratégie de label de sensibilité qui décrit le label de sensibilité. Lecture/écriture java.util.UUID.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```

Indique si le label de sensibilité est activé.

**Returns:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```

Indique si le label de sensibilité est activé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```

Indique si le label de sensibilité a été supprimé.

**Returns:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```

Indique si le label de sensibilité a été supprimé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```

Renvoie ou définit la méthode d'affectation du label de sensibilité. Lecture/écriture [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Returns:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```

Renvoie ou définit la méthode d'affectation du label de sensibilité. Lecture/écriture [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

Renvoie la liste des types de marquage de contenu qui doivent être appliqués à un fichier.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Une liste de types de contenu [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)