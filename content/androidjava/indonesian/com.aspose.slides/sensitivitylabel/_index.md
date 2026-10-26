---
title: SensitivityLabel
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili label sensitivitas dari Microsoft Purview Information Protection.
type: docs
url: /id/com.aspose.slides/sensitivitylabel/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

Mewakili label sensitivitas dari Microsoft Purview Information Protection.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getId()](#getId--) | Mengembalikan atau mengatur id label sensitivitas. |
| [setId(String value)](#setId-java.lang.String-) | Mengembalikan atau mengatur id label sensitivitas. |
| [getSiteId()](#getSiteId--) | Mengembalikan atau mengatur pengidentifikasi situs Azure Active Directory (Azure AD) yang sesuai dengan kebijakan label sensitivitas yang menggambarkan label sensitivitas. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Mengembalikan atau mengatur pengidentifikasi situs Azure Active Directory (Azure AD) yang sesuai dengan kebijakan label sensitivitas yang menggambarkan label sensitivitas. |
| [isEnabled()](#isEnabled--) | Menunjukkan apakah label sensitivitas diaktifkan. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Menunjukkan apakah label sensitivitas diaktifkan. |
| [isRemoved()](#isRemoved--) | Menunjukkan apakah label sensitivitas telah dihapus. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Menunjukkan apakah label sensitivitas telah dihapus. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Mengembalikan atau mengatur metode penugasan untuk label sensitivitas. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Mengembalikan atau mengatur metode penugasan untuk label sensitivitas. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Mengembalikan daftar jenis penandaan konten yang harus diterapkan pada sebuah file. |
### getId() {#getId--}
```
public final String getId()
```


Mengembalikan atau mengatur id label sensitivitas. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```


Mengembalikan atau mengatur id label sensitivitas. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```


Mengembalikan atau mengatur pengidentifikasi situs Azure Active Directory (Azure AD) yang sesuai dengan kebijakan label sensitivitas yang menggambarkan label sensitivitas. Baca/tulis java.util.UUID.

**Mengembalikan:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```


Mengembalikan atau mengatur pengidentifikasi situs Azure Active Directory (Azure AD) yang sesuai dengan kebijakan label sensitivitas yang menggambarkan label sensitivitas. Baca/tulis java.util.UUID.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```


Menunjukkan apakah label sensitivitas diaktifkan.

**Mengembalikan:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Menunjukkan apakah label sensitivitas diaktifkan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```


Menunjukkan apakah label sensitivitas telah dihapus.

**Mengembalikan:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```


Menunjukkan apakah label sensitivitas telah dihapus.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```


Mengembalikan atau mengatur metode penugasan untuk label sensitivitas. Baca/tulis [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Mengembalikan:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```


Mengembalikan atau mengatur metode penugasan untuk label sensitivitas. Baca/tulis [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


Mengembalikan daftar jenis penandaan konten yang harus diterapkan pada sebuah file.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Daftar jenis konten [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)