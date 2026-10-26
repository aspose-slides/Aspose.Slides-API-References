---
title: ISensitivityLabel
second_title: Aspose.Slides for Java API Reference
description: Represents the sensitivity label from Microsoft Purview Information Protection.
type: docs
url: /tr/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Microsoft Purview Information Protection'dan duyarlılık etiketini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getId()](#getId--) | Duyarlılık etiketinin kimliğini döndürür veya ayarlar. |
| [setId(String value)](#setId-java.lang.String-) | Duyarlılık etiketinin kimliğini döndürür veya ayarlar. |
| [getSiteId()](#getSiteId--) | Duyarlılık etiketini tanımlayan duyarlılık etiketi politikasına karşılık gelen Azure Active Directory (Azure AD) site tanımlayıcısını döndürür veya ayarlar. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Duyarlılık etiketini tanımlayan duyarlılık etiketi politikasına karşılık gelen Azure Active Directory (Azure AD) site tanımlayıcısını döndürür veya ayarlar. |
| [isEnabled()](#isEnabled--) | Duyarlılık etiketinin etkin olup olmadığını gösterir. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Duyarlılık etiketinin etkin olup olmadığını gösterir. |
| [isRemoved()](#isRemoved--) | Duyarlılık etiketinin kaldırılıp kaldırılmadığını gösterir. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Duyarlılık etiketinin kaldırılıp kaldırılmadığını gösterir. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Duyarlılık etiketi için atama yöntemini döndürür veya ayarlar. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Duyarlılık etiketi için atama yöntemini döndürür veya ayarlar. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Bir dosyaya uygulanması gereken içerik işaretleme türlerinin listesini döndürür. |
### getId() {#getId--}
```
public abstract String getId()
```


Duyarlılık etiketinin kimliğini döndürür veya ayarlar. Okunur/yazılır String.

**Döndürür:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```


Duyarlılık etiketinin kimliğini döndürür veya ayarlar. Okunur/yazılır String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```


Duyarlılık etiketini tanımlayan duyarlılık etiketi politikasına karşılık gelen Azure Active Directory (Azure AD) site tanımlayıcısını döndürür veya ayarlar. Okunur/yazılır java.util.UUID.

**Döndürür:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```


Duyarlılık etiketini tanımlayan duyarlılık etiketi politikasına karşılık gelen Azure Active Directory (Azure AD) site tanımlayıcısını döndürür veya ayarlar. Okunur/yazılır java.util.UUID.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```


Duyarlılık etiketinin etkin olup olmadığını gösterir.

**Döndürür:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```


Duyarlılık etiketinin etkin olup olmadığını gösterir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```


Duyarlılık etiketinin kaldırılıp kaldırılmadığını gösterir.

**Döndürür:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```


Duyarlılık etiketinin kaldırılıp kaldırılmadığını gösterir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```


Duyarlılık etiketi için atama yöntemini döndürür veya ayarlar. Okunur/yazılır [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Döndürür:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```


Duyarlılık etiketi için atama yöntemini döndürür veya ayarlar. Okunur/yazılır [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


Bir dosyaya uygulanması gereken içerik işaretleme türlerinin listesini döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - İçerik türlerinin bir listesi [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)