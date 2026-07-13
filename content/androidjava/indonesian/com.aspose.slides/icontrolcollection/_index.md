---
title: IControlCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Koleksi kontrol ActiveX.
type: docs
url: /id/com.aspose.slides/icontrolcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

Koleksi kontrol ActiveX.
## Metode

| Method | Deskripsi |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Menghapus kontrol ActiveX dari koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus kontrol ActiveX yang disimpan pada posisi yang ditentukan dari koleksi. |
| [clear()](#clear--) | Menghapus semua kontrol dari koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan kontrol pada posisi yang ditentukan. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Membuat dan menambahkan kontrol baru ke koleksi. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

Menghapus kontrol ActiveX dari koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Kontrol yang akan dihapus. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Menghapus kontrol ActiveX yang disimpan pada posisi yang ditentukan dari koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks kontrol yang akan dihapus. |

### clear() {#clear--}
```
public abstract void clear()
```

Menghapus semua kontrol dari koleksi.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

Mengembalikan kontrol pada posisi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks kontrol. |

**Mengembalikan:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

Membuat dan menambahkan kontrol baru ke koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| controlType | int | Tipe kontrol yang akan ditambahkan. |
| x | float | Koordinat X untuk sisi kiri bingkai bentuk. |
| y | float | Koordinat Y untuk sisi atas bingkai bentuk. |
| width | float | Lebar bingkai bentuk. |
| height | float | Tinggi bingkai bentuk. |

**Mengembalikan:**
[IControl](../../com.aspose.slides/icontrol) - Kontrol yang dibuat [IControl](../../com.aspose.slides/icontrol).