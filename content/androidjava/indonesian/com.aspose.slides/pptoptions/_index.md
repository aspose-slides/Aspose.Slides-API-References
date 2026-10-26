---
title: PptOptions
second_title: Referensi API Java Aspose.Slides untuk Android
description: Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format PPT.
type: docs
url: /id/com.aspose.slides/pptoptions/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IPptOptions](../../com.aspose.slides/ipptoptions), java.lang.Cloneable
```
public class PptOptions extends SaveOptions implements IPptOptions, Cloneable
```

Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format PPT.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Mewakili GUID kelas objek (CLSID) yang disimpan dalam entri direktori root. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Mewakili GUID kelas objek (CLSID) yang disimpan dalam entri direktori root. |
### PptOptions() {#PptOptions--}
```
public PptOptions()
```

### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public final UUID getRootDirectoryClsid()
```

Mewakili GUID kelas objek (CLSID) yang disimpan dalam entri direktori root. Dapat digunakan untuk aktivasi COM aplikasi dokumen. Nilai default adalah '64818D11-4F9B-11CF-86EA-00AA00B929E8' yang sesuai dengan 'Microsoft Powerpoint.Slide.8'.

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
public final void setRootDirectoryClsid(UUID value)
```

Mewakili GUID kelas objek (CLSID) yang disimpan dalam entri direktori root. Dapat digunakan untuk aktivasi COM aplikasi dokumen. Nilai default adalah '64818D11-4F9B-11CF-86EA-00AA00B929E8' yang sesuai dengan 'Microsoft Powerpoint.Slide.8'.

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