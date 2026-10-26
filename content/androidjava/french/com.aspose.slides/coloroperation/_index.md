---
title: ColorOperation
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente différentes opérations de couleur utilisées pour les transformations de couleur.
type: docs
url: /fr/com.aspose.slides/coloroperation/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

Représente différentes opérations de couleur utilisées pour les transformations de couleur. Objet immuable.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Crée une nouvelle opération de transformation de couleur. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Crée une nouvelle opération de transformation de couleur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getOperationType()](#getOperationType--) | Renvoie ou définit le type d'une opération. |
| [getParameter()](#getParameter--) | Renvoie un paramètre d'une opération. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si les deux instances de ColorOperation sont égales. |
| [hashCode()](#hashCode--) | Servir de fonction de hachage pour un type particulier, adaptée à une utilisation dans des algorithmes de hachage et des structures de données telles qu'une table de hachage. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

Crée une nouvelle opération de transformation de couleur.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| op | int | Type d'opération. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

Crée une nouvelle opération de transformation de couleur.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| op | int | Type d'opération. |
| parameter | float | Paramètre de l'opération. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

Renvoie ou définit le type d'une opération. Lecture seule [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Renvoie:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```

Renvoie un paramètre d'une opération. Lecture seule float.

**Renvoie:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Détermine si les deux instances de ColorOperation sont égales.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le ColorOperation à comparer avec le ColorOperation actuel. |

**Renvoie:**
boolean - **true** si le ColorOperation spécifié est égal au ColorOperation actuel ; sinon, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Servir de fonction de hachage pour un type particulier, adaptée à une utilisation dans des algorithmes de hachage et des structures de données telles qu'une table de hachage.

**Renvoie:**
int