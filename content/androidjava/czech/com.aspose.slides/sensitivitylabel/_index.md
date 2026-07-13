---
title: SensitivityLabel
second_title: Aspose.Slides pro Android - reference Java API
description: Reprezentuje citlivostní štítek ze služby Microsoft Purview Information Protection.
type: docs
url: /cs/com.aspose.slides/sensitivitylabel/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

Represents the sensitivity label from Microsoft Purview Information Protection.

## Metody

| Metoda | Popis |
| --- | --- |
| [getId()](#getId--) | Vrací nebo nastavuje id citlivostního štítku. |
| [setId(String value)](#setId-java.lang.String-) | Vrací nebo nastavuje id citlivostního štítku. |
| [getSiteId()](#getSiteId--) | Vrací nebo nastavuje identifikátor webu Azure Active Directory (Azure AD), který odpovídá zásadě citlivostního štítku popisující citlivostní štítek. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Vrací nebo nastavuje identifikátor webu Azure Active Directory (Azure AD), který odpovídá zásadě citlivostního štítku popisující citlivostní štítek. |
| [isEnabled()](#isEnabled--) | Indikuje, zda je citlivostní štítek povolen. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Indikuje, zda je citlivostní štítek povolen. |
| [isRemoved()](#isRemoved--) | Indikuje, zda byl citlivostní štítek odstraněn. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Indikuje, zda byl citlivostní štítek odstraněn. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Vrací nebo nastavuje způsob přiřazení pro citlivostní štítek. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Vrací nebo nastavuje způsob přiřazení pro citlivostní štítek. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Vrací seznam typů označování obsahu, které by měly být aplikovány na soubor. |
### getId() {#getId--}
```
public final String getId()
```

Vrací nebo nastavuje id citlivostního štítku. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```

Vrací nebo nastavuje id citlivostního štítku. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```

Vrací nebo nastavuje identifikátor webu Azure Active Directory (Azure AD), který odpovídá zásadě citlivostního štítku popisující citlivostní štítek. Čtení/Zápis java.util.UUID.

**Vrací:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```

Vrací nebo nastavuje identifikátor webu Azure Active Directory (Azure AD), který odpovídá zásadě citlivostního štítku popisující citlivostní štítek. Čtení/Zápis java.util.UUID.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```

Indikuje, zda je citlivostní štítek povolen.

**Vrací:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```

Indikuje, zda je citlivostní štítek povolen.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```

Indikuje, zda byl citlivostní štítek odstraněn.

**Vrací:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```

Indikuje, zda byl citlivostní štítek odstraněn.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```

Vrací nebo nastavuje způsob přiřazení pro citlivostní štítek. Čtení/Zápis [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Vrací:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```

Vrací nebo nastavuje způsob přiřazení pro citlivostní štítek. Čtení/Zápis [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

Vrací seznam typů označování obsahu, které by měly být aplikovány na soubor.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - A list of content types [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)