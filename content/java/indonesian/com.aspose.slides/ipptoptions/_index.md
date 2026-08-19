---
title: IPptOptions
second_title: Referensi API Aspose.Slides untuk Java
description: Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format PPT.
type: docs
url: /id/com.aspose.slides/ipptoptions/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format PPT.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Mewakili GUID kelas objek (CLSID) yang disimpan dalam entri direktori root. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Mewakili GUID kelas objek (CLSID) yang disimpan dalam entri direktori root. |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```


Mewakili GUID kelas objek (CLSID) yang disimpan dalam entri direktori root. Dapat digunakan untuk aktivasi COM dari aplikasi dokumen. Nilai default adalah '64818D11-4F9B-11CF-86EA-00AA00B929E8' yang sesuai dengan 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// atur CLSID ke 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public abstract void setRootDirectoryClsid(UUID value)
```


Mewakili GUID kelas objek (CLSID) yang disimpan dalam entri direktori root. Dapat digunakan untuk aktivasi COM dari aplikasi dokumen. Nilai default adalah '64818D11-4F9B-11CF-86EA-00AA00B929E8' yang sesuai dengan 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// atur CLSID ke 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.UUID |  |