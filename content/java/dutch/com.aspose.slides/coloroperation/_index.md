---
title: ColorOperation
second_title: Aspose.Slides voor Java API-referentie
description: Stelt verschillende kleurbewerkingen voor die worden gebruikt voor kleurtransformaties.
type: docs
url: /nl/com.aspose.slides/coloroperation/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

Stelt verschillende kleurbewerkingen voor die worden gebruikt voor kleurtransformaties. Onveranderlijk object.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Maakt een nieuwe kleurtransformatiebewerking. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Maakt een nieuwe kleurtransformatiebewerking. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getOperationType()](#getOperationType--) | Geeft of stelt het type van een bewerking in. |
| [getParameter()](#getParameter--) | Geeft een parameter van een bewerking terug. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de twee ColorOperation-instanties gelijk zijn. |
| [hashCode()](#hashCode--) | Dient als een hash-functie voor een bepaald type, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hashtabel. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

Maakt een nieuwe kleurtransformatiebewerking.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| op | int | Type bewerking. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

Maakt een nieuwe kleurtransformatiebewerking.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| op | int | Type bewerking. |
| parameter | float | Parameter van de bewerking. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

Geeft of stelt het type van een bewerking in. Alleen-lezen [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Retour:**  
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```

Geeft een parameter van een bewerking terug. Alleen-lezen float.

**Retour:**  
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bepaalt of de twee ColorOperation-instanties gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | De ColorOperation om te vergelijken met de huidige ColorOperation. |

**Retour:**
boolean - **true** als de opgegeven ColorOperation gelijk is aan de huidige ColorOperation; anders, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als een hash-functie voor een bepaald type, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hashtabel.

**Retour:**  
int