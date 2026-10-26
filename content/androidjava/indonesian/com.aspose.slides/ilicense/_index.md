---
title: ILicense
second_title: Aspose.Slides for Android via Java API Reference
description: Provides methods to license the component.
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

| Method | Description |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Memberi lisensi pada komponen. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Memberi lisensi pada komponen. |
| [resetLicense()](#resetLicense--) | Reset lisensi |
| [isLicensed()](#isLicensed--) | Periksa apakah lisensi diterapkan pada komponen |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```


Memberi lisensi pada komponen.

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
| licenseName | java.lang.String | Dapat berupa nama file lengkap atau singkat atau nama sumber daya terbenam. Gunakan string kosong untuk beralih ke mode evaluasi.

--------------------

Mencoba menemukan lisensi di lokasi berikut:

1. Jalur eksplisit.

2. Folder assembly komponen.

3. Folder assembly pemanggil klien.

4. Folder assembly entri.

5. Sumber daya terbenam di assembly pemanggil klien. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```


Memberi lisensi pada komponen.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran yang berisi lisensi.

--------------------

Gunakan metode ini untuk memuat lisensi dari aliran. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```


Reset lisensi

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```


--------------------

Gunakan metode ini untuk mereset lisensi dalam komponen

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```


Periksa apakah lisensi diterapkan pada komponen

**Mengembalikan:**
boolean - true jika komponen berlisensi, jika tidak false