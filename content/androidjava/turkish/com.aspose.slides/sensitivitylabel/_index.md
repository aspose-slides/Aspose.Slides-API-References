---
title: SensitivityLabel
second_title: Aspose.Slides for Android Java API Referansı
description: Microsoft Purview Information Protection'tan gelen duyarlılık etiketini temsil eder.
type: docs
url: /tr/com.aspose.slides/sensitivitylabel/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
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
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Duyarlılık etiketinin atama yöntemini döndürür veya ayarlar. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Duyarlılık etiketinin atama yöntemini döndürür veya ayarlar. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Bir dosyaya uygulanması gereken içerik işaretleme türlerinin listesini döndürür. |
### getId() {#getId--}
```
public final String getId()
```

Duyarlılık etiketinin kimliğini döndürür veya ayarlar. Okuma/Yazma String.

**Döndürür:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```

Duyarlılık etiketinin kimliğini döndürür veya ayarlar. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```

Duyarlılık etiketini tanımlayan duyarlılık etiketi politikasına karşılık gelen Azure Active Directory (Azure AD) site tanımlayıcısını döndürür veya ayarlar. Okuma/Yazma java.util.UUID.

**Döndürür:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```

Duyarlılık etiketini tanımlayan duyarlılık etiketi politikasına karşılık gelen Azure Active Directory (Azure AD) site tanımlayıcısını döndürür veya ayarlar. Okuma/Yazma java.util.UUID.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```

Duyarlılık etiketinin etkin olup olmadığını gösterir.

**Döndürür:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```

Duyarlılık etiketinin etkin olup olmadığını gösterir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```

Duyarlılık etiketinin kaldırılıp kaldırılmadığını gösterir.

**Döndürür:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```

Duyarlılık etiketinin kaldırılıp kaldırılmadığını gösterir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```

Duyarlılık etiketinin atama yöntemini döndürür veya ayarlar. Okuma/Yazma [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Döndürür:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```

Duyarlılık etiketinin atama yöntemini döndürür veya ayarlar. Okuma/Yazma [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

Bir dosyaya uygulanması gereken içerik işaretleme türlerinin listesini döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - İçerik türlerinin bir listesi [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)