---
title: ICaptions
second_title: Aspose.Slides for Android via Java API Reference
description: Mewakili caption tertutup WebVTT.
type: docs
url: /id/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

Mewakili caption tertutup WebVTT.
## Metode

| Method | Description |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Mengembalikan pengidentifikasi unik global (GUID) dari caption tertutup. |
| [getLabel()](#getLabel--) | Mengembalikan atau mengatur label caption tertutup. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Mengembalikan atau mengatur label caption tertutup. |
| [getBinaryData()](#getBinaryData--) | Mengembalikan data biner caption tertutup. |
| [getDataAsString()](#getDataAsString--) | Mengembalikan data caption tertutup sebagai string yang dikodekan UTF-8. Hanya-baca String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```


Mengembalikan pengidentifikasi unik global (GUID) dari caption tertutup. Hanya-baca java.util.UUID.

**Mengembalikan:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```


Mengembalikan atau mengatur label caption tertutup. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```


Mengembalikan atau mengatur label caption tertutup. Baca/tulis String.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Mengembalikan data biner caption tertutup. Hanya-baca byte[].

**Mengembalikan:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```


Mengembalikan data caption tertutup sebagai string yang dikodekan UTF-8. Hanya-baca String.

**Mengembalikan:**
java.lang.String