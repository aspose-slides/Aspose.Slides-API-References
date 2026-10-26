---
title: IControl
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili kontrol ActiveX.
type: docs
url: /id/com.aspose.slides/icontrol/
---
**Semua Interface yang Diimplementasikan:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

Mewakili kontrol ActiveX.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getName()](#getName--) | Mengembalikan nama kontrol ini. |
| [setName(String value)](#setName-java.lang.String-) | Mengembalikan nama kontrol ini. |
| [getClassId()](#getClassId--) | Mendapatkan class id dari kontrol ini. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Mengembalikan objek properti isi gambar ControlEx. |
| [getFrame()](#getFrame--) | Mengembalikan atau mengatur bingkai kontrol. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Mengembalikan atau mengatur bingkai kontrol. |
| [getProperties()](#getProperties--) | Mengembalikan koleksi properti ActiveX. |
| [getPersistence()](#getPersistence--) | Mendapatkan metode yang digunakan untuk menyimpan properti kontrol ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Menentukan persistensi kontrol ActiveX ketika metode yang digunakan untuk persistensi adalah PersistStream, PersistStreamInit atau PersistStorage. |
### getName() {#getName--}
```
public abstract String getName()
```


Mengembalikan nama kontrol ini. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Mengembalikan nama kontrol ini. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```


Mendapatkan class id dari kontrol ini. Hanya-baca java.util.UUID.

**Mengembalikan:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```


Mengembalikan objek properti isi gambar ControlEx. Hanya-baca [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Mengembalikan:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```


Mengembalikan atau mengatur bingkai kontrol. Baca/tulis [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Mengembalikan:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```


Mengembalikan atau mengatur bingkai kontrol. Baca/tulis [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```


Mengembalikan koleksi properti ActiveX. Hanya-baca [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**Mengembalikan:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```


Mendapatkan metode yang digunakan untuk menyimpan properti kontrol ActiveX. Hanya-baca [PersistenceType](../../com.aspose.slides/persistencetype).

**Mengembalikan:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```


Menentukan persistensi kontrol ActiveX ketika metode yang digunakan untuk persistensi adalah PersistStream, PersistStreamInit atau PersistStorage.

**Mengembalikan:**
byte[]