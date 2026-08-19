---
title: ILicense
second_title: Aspose.Slides for Java API Reference
description: Menyediakan metode untuk melisensikan komponen.
type: docs
url: /id/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Menyediakan metode untuk melisensikan komponen.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Menerapkan lisensi pada komponen. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Menerapkan lisensi pada komponen. |
| [resetLicense()](#resetLicense--) | Mengatur ulang lisensi |
| [isLicensed()](#isLicensed--) | Memeriksa apakah lisensi telah diterapkan pada komponen |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```

Menerapkan lisensi pada komponen.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| licenseName | java.lang.String | Dapat berupa nama file lengkap atau singkat atau nama sumber daya yang disematkan. Gunakan string kosong untuk beralih ke mode evaluasi. |

--------------------

Mencoba menemukan lisensi di lokasi berikut:

1. Jalur eksplisit.
2. Folder assembly komponen.
3. Folder assembly pemanggil klien.
4. Folder entry assembly.
5. Sumber daya yang disematkan di assembly pemanggil klien. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```

Menerapkan lisensi pada komponen.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran yang berisi lisensi. |

--------------------

Gunakan metode ini untuk memuat lisensi dari aliran. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```

Mengatur ulang lisensi

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

Gunakan metode ini untuk mengatur ulang lisensi dalam komponen

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```

Memeriksa apakah lisensi telah diterapkan pada komponen

**Mengembalikan:**
boolean - true jika komponen memiliki lisensi, jika tidak false