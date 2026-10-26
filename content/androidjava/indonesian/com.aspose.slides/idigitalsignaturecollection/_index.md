---
title: IDigitalSignatureCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili koleksi tanda tangan digital yang terlampir pada dokumen.
type: docs
url: /id/com.aspose.slides/idigitalsignaturecollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

Mewakili koleksi tanda tangan digital yang terlampir pada dokumen.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan tanda tangan berdasarkan indeks. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | Menambahkan tanda tangan di akhir koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus tanda tangan pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua tanda tangan dari koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```

Mengembalikan tanda tangan berdasarkan indeks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
```

Menambahkan tanda tangan di akhir koleksi.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      signature.setComments("Aspose.Slides digital signing test.");
>      pres.getDigitalSignatures().add(signature);
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Tanda tangan untuk ditambahkan. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Menghapus tanda tangan pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks tanda tangan yang harus dihapus. |

### clear() {#clear--}
```
public abstract void clear()
```

Menghapus semua tanda tangan dari koleksi.