---
title: License
second_title: Referensi API Aspose.Slides untuk Java
description: Menyediakan metode untuk melisensikan komponen.
type: docs
url: /id/com.aspose.slides/license/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

Menyediakan metode untuk melisensikan komponen.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

## Konstruktor

| Constructor | Deskripsi |
| --- | --- |
| [License()](#License--) | Menginisialisasi instance baru dari kelas ini. |
## Metode

| Method | Deskripsi |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Melisensikan komponen. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Melisensikan komponen. |
| [getVersion()](#getVersion--) | Mengembalikan versi Aspose.Slides untuk Java. |
| [resetLicense()](#resetLicense--) | Reset lisensi. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```

Menginisialisasi instance baru dari kelas ini.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```

Melisensikan komponen.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran yang berisi lisensi. Gunakan null untuk beralih ke mode evaluasi. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```

Melisensikan komponen.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| namePath | java.lang.String | Dapat berupa nama file lengkap atau nama pendek atau nama sumber daya yang disematkan. Gunakan string kosong untuk beralih ke mode evaluasi. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```

Mengembalikan versi Aspose.Slides untuk Java.

**Mengembalikan:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```

Reset lisensi. Gunakan metode ini untuk mereset lisensi dalam komponen.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```

Periksa apakah lisensi sudah diterapkan pada komponen.

**Mengembalikan:**
boolean