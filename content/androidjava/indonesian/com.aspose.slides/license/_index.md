---
title: License
second_title: Referensi API Java Aspose.Slides untuk Android
description: Menyediakan metode untuk melisensikan komponen.
type: docs
url: /id/com.aspose.slides/license/
---
**Pewarisan:**
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

| Konstruktor | Deskripsi |
| --- | --- |
| [License()](#License--) | Menginisialisasi instance baru dari kelas ini. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Melisensikan komponen. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Melisensikan komponen. |
| [getVersion()](#getVersion--) | Mengembalikan versi Aspose.Slides untuk Android melalui Java. |
| [resetLicense()](#resetLicense--) | Mengatur ulang lisensi. |
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
| namePath | java.lang.String | Dapat berupa nama file lengkap atau pendek atau nama sumber daya tersemat. Gunakan string kosong untuk beralih ke mode evaluasi. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```


Mengembalikan versi Aspose.Slides untuk Android melalui Java.

**Mengembalikan:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```


Mengatur ulang lisensi. Gunakan metode ini untuk mengatur ulang lisensi pada komponen.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```


### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```


Memeriksa apakah lisensi telah diterapkan pada komponen

**Mengembalikan:**
boolean