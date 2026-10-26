---
title: ColorOperation
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt verschillende kleurbewerkingen die worden gebruikt voor kleurtransformaties.
type: docs
url: /nl/com.aspose.slides/coloroperation/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

Vertegenwoordigt verschillende kleurbewerkingen die worden gebruikt voor kleurtransformaties. Niet-mutabel object.
## Constructors

| Constructor | Description |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Maakt een nieuwe kleurtransformatie-bewerking. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Maakt een nieuwe kleurtransformatie-bewerking. |
## Methods

| Method | Description |
| --- | --- |
| [getOperationType()](#getOperationType--) | Retourneert of zet het type van een bewerking. |
| [getParameter()](#getParameter--) | Retourneert een parameter van een bewerking. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de twee ColorOperation-instanties gelijk zijn. |
| [hashCode()](#hashCode--) | Dient als een hash-functie voor een specifiek type, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hash-tabel. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

Maakt een nieuwe kleurtransformatie-bewerking.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | int | Type bewerking. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

Maakt een nieuwe kleurtransformatie-bewerking.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | int | Type bewerking. |
| parameter | float | Parameter van de bewerking. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

Retourneert of zet het type van een bewerking. Alleen-lezen [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Retour:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```

Retourneert een parameter van een bewerking. Alleen-lezen float.

**Retour:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bepaalt of de twee ColorOperation-instanties gelijk zijn.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | De ColorOperation om te vergelijken met de huidige ColorOperation. |

**Retour:**
boolean - **true** als de opgegeven ColorOperation gelijk is aan de huidige ColorOperation; anders **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als een hash-functie voor een specifiek type, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hash-tabel.

**Retour:**
int