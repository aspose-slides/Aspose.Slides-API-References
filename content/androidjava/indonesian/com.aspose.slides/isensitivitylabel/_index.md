---
title: ISensitivityLabel
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili label sensitivitas dari Microsoft Purview Information Protection.
type: docs
url: /id/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
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
| [getContentMarkTypes()](#getContentMarkTypes--) | Mengembalikan daftar jenis penandaan konten yang harus diterapkan pada file. |
### getId() {#getId--}
```
public abstract String getId()
```


Mengembalikan atau mengatur id label sensitivitas. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```


Mengembalikan atau mengatur id label sensitivitas. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```


Mengembalikan atau mengatur pengidentifikasi situs Azure Active Directory (Azure AD) yang sesuai dengan kebijakan label sensitivitas yang menggambarkan label sensitivitas. Baca/tulis java.util.UUID.

**Mengembalikan:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```


Mengembalikan atau mengatur pengidentifikasi situs Azure Active Directory (Azure AD) yang sesuai dengan kebijakan label sensitivitas yang menggambarkan label sensitivitas. Baca/tulis java.util.UUID.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```


Menunjukkan apakah label sensitivitas diaktifkan.

**Mengembalikan:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```


Menunjukkan apakah label sensitivitas diaktifkan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```


Menunjukkan apakah label sensitivitas telah dihapus.

**Mengembalikan:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```


Menunjukkan apakah label sensitivitas telah dihapus.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```


Mengembalikan atau mengatur metode penugasan untuk label sensitivitas. Baca/tulis [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Mengembalikan:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```


Mengembalikan atau mengatur metode penugasan untuk label sensitivitas. Baca/tulis [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


Mengembalikan daftar jenis penandaan konten yang harus diterapkan pada file.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Daftar tipe konten [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)