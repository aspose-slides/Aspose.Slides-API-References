---
title: ICaptions
second_title: Aspose.Slides for Java API Reference
description: Mewakili caption tertutup WebVTT.
type: docs
url: /id/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

Mewakili caption tertutup WebVTT.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Mengembalikan pengenal unik global (GUID) dari caption tertutup. |
| [getLabel()](#getLabel--) | Mengembalikan atau mengatur label dari caption tertutup. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Mengembalikan atau mengatur label dari caption tertutup. |
| [getBinaryData()](#getBinaryData--) | Mengembalikan data biner dari caption tertutup. |
| [getDataAsString()](#getDataAsString--) | Mengembalikan data caption tertutup sebagai string ber-encoding UTF-8 Baca-saja String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```


Mengembalikan pengenal unik global (GUID) dari caption tertutup. Baca-saja java.util.UUID.

**Mengembalikan:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```


Mengembalikan atau mengatur label dari caption tertutup. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```


Mengembalikan atau mengatur label dari caption tertutup. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Mengembalikan data biner dari caption tertutup. Baca-saja byte[].

**Mengembalikan:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```


Mengembalikan data caption tertutup sebagai string ber-encoding UTF-8 Baca-saja String.

**Mengembalikan:**
java.lang.String