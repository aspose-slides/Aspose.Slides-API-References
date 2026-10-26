---
title: Control
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili kontrol ActiveX.
type: docs
url: /id/com.aspose.slides/control/
---
**Pewarisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)
```
public class Control extends DomObject<ControlCollection> implements IControl
```

Mewakili kontrol ActiveX.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPersistence()](#getPersistence--) | Mendapatkan metode yang digunakan untuk menyimpan properti kontrol ActiveX. |
| [getName()](#getName--) | Mendapatkan atau mengatur nama kontrol ini. |
| [setName(String value)](#setName-java.lang.String-) | Mendapatkan atau mengatur nama kontrol ini. |
| [getClassId()](#getClassId--) | Mendapatkan ID kelas kontrol ini. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | Mendapatkan ID kelas kontrol ini. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Mengembalikan objek properti isi gambar kontrol. |
| [getFrame()](#getFrame--) | Mengembalikan atau mengatur bingkai kontrol. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Mengembalikan atau mengatur bingkai kontrol. |
| [getProperties()](#getProperties--) | Mengembalikan koleksi properti ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Menentukan keberlangsungan kontrol ActiveX ketika metode yang digunakan untuk persisten adalah PersistStream, PersistStreamInit, atau PersistStorage. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |

### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

Mendapatkan metode yang digunakan untuk menyimpan properti kontrol ActiveX. Hanya baca [PersistenceType](../../com.aspose.slides/persistencetype).

--------------------

> ```
> Next example shows the using Persistence property for checking if properties of ActiveX object may be changed as XML based ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //Gunakan metode Anda sendiri untuk mengelola properti ActiveX yang disimpan dalam file biner tersebut
>  }
> ```

**Mengembalikan:**
int
### getName() {#getName--}
```
public final String getName()
```

Mendapatkan atau mengatur nama kontrol ini. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Mendapatkan atau mengatur nama kontrol ini. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

Mendapatkan ID kelas kontrol ini. Hanya baca java.util.UUID.

**Mengembalikan:**
java.util.UUID
### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

Mendapatkan ID kelas kontrol ini. Hanya baca java.util.UUID.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Mengembalikan objek properti isi gambar kontrol. Hanya baca [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Mengembalikan:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Mengembalikan atau mengatur bingkai kontrol. Baca/tulis [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Mengembalikan:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Mengembalikan atau mengatur bingkai kontrol. Baca/tulis [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

Mengembalikan koleksi properti ActiveX. Hanya baca [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

Catatan: Aspose.Slides mendukung hanya properti ActiveX berbasis XML. Jika properti disimpan dalam format biner, properti ini akan mengembalikan null.

**Mengembalikan:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

Menentukan keberlangsungan kontrol ActiveX ketika metode yang digunakan untuk persisten adalah PersistStream, PersistStreamInit, atau PersistStorage.

--------------------

> ```
> Next example shows the using ActiveXControlBinary property for changing ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //Gunakan metode Anda sendiri untuk mengelola properti ActiveX yang disimpan dalam file biner tersebut
>  }
> ```

**Mengembalikan:**
byte[]
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Mengembalikan slide dasar. Hanya baca [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan presentasi. Hanya baca [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)