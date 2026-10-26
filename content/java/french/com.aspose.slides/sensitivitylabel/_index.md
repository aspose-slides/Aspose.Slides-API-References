---
title: SensitivityLabel
second_title: Référence API Aspose.Slides pour Java
description: Représente le libellé de sensibilité de Microsoft Purview Information Protection.
type: docs
url: /fr/com.aspose.slides/sensitivitylabel/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)  
```
public final class SensitivityLabel implements ISensitivityLabel
```

Représente le libellé de sensibilité de Microsoft Purview Information Protection.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getId()](#getId--) | Renvoie ou définit l'identifiant du libellé de sensibilité. |
| [setId(String value)](#setId-java.lang.String-) | Renvoie ou définit l'identifiant du libellé de sensibilité. |
| [getSiteId()](#getSiteId--) | Renvoie ou définit l'identifiant du site Azure Active Directory (Azure AD) correspondant à la stratégie de libellé de sensibilité qui décrit le libellé de sensibilité. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Renvoie ou définit l'identifiant du site Azure Active Directory (Azure AD) correspondant à la stratégie de libellé de sensibilité qui décrit le libellé de sensibilité. |
| [isEnabled()](#isEnabled--) | Indique si le libellé de sensibilité est activé. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Indique si le libellé de sensibilité est activé. |
| [isRemoved()](#isRemoved--) | Indique si le libellé de sensibilité a été supprimé. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Indique si le libellé de sensibilité a été supprimé. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Renvoie ou définit la méthode d'affectation du libellé de sensibilité. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Renvoie ou définit la méthode d'affectation du libellé de sensibilité. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Renvoie la liste des types de marquage de contenu qui doivent être appliqués à un fichier. |
### getId() {#getId--}
```
public final String getId()
```

Renvoie ou définit l'identifiant du libellé de sensibilité. Lecture/écriture String.

**Renvoie :**  
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```

Renvoie ou définit l'identifiant du libellé de sensibilité. Lecture/écriture String.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```

Renvoie ou définit l'identifiant du site Azure Active Directory (Azure AD) correspondant à la stratégie de libellé de sensibilité qui décrit le libellé de sensibilité. Lecture/écriture java.util.UUID.

**Renvoie :**  
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```

Renvoie ou définit l'identifiant du site Azure Active Directory (Azure AD) correspondant à la stratégie de libellé de sensibilité qui décrit le libellé de sensibilité. Lecture/écriture java.util.UUID.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```

Indique si le libellé de sensibilité est activé.

**Renvoie :**  
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```

Indique si le libellé de sensibilité est activé.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```

Indique si le libellé de sensibilité a été supprimé.

**Renvoie :**  
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```

Indique si le libellé de sensibilité a été supprimé.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```

Renvoie ou définit la méthode d'affectation du libellé de sensibilité. Lecture/écriture [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Renvoie :**  
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```

Renvoie ou définit la méthode d'affectation du libellé de sensibilité. Lecture/écriture [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

Renvoie la liste des types de marquage de contenu qui doivent être appliqués à un fichier.

**Renvoie :**  
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Une liste des types de contenu [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)