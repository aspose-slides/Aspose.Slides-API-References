---
title: BlobManagementOptions
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili opsi yang dapat digunakan untuk mengelola aturan penanganan BLOB dan pengaturan BLOB lainnya.
type: docs
url: /id/com.aspose.slides/blobmanagementoptions/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

Mewakili opsi yang dapat digunakan untuk mengelola aturan penanganan BLOB dan pengaturan BLOB lainnya.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Membuat opsi manajemen blob default baru. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Properti ini menentukan apakah instance dari kelas Presentation dapat menjadi pemilik sumber - file atau stream selama masa hidup instance. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Properti ini menentukan apakah instance dari kelas Presentation dapat menjadi pemilik sumber - file atau stream selama masa hidup instance. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Properti ini menentukan apakah file sementara dapat dibuat saat bekerja dengan BLOB, yang secara signifikan mengurangi konsumsi memori tetapi memerlukan izin untuk membuat file. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Properti ini menentukan apakah file sementara dapat dibuat saat bekerja dengan BLOB, yang secara signifikan mengurangi konsumsi memori tetapi memerlukan izin untuk membuat file. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Jalur akar tempat file sementara akan dibuat. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Jalur akar tempat file sementara akan dibuat. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Menentukan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB di memori. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Menentukan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB di memori. |
### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```


Membuat opsi manajemen blob default baru.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```


Properti ini menentukan apakah instance dari kelas Presentation dapat menjadi pemilik sumber - file atau stream selama masa hidup instance. Jika instance menjadi pemilik, ia mengunci sumber. Ini membantu meningkatkan konsumsi memori dan kinerja saat bekerja dengan BLOB, tetapi sumber (stream atau file) tidak dapat diubah selama masa hidup instance Presentation.

**Mengembalikan:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```


Properti ini menentukan apakah instance dari kelas Presentation dapat menjadi pemilik sumber - file atau stream selama masa hidup instance. Jika instance menjadi pemilik, ia mengunci sumber. Ini membantu meningkatkan konsumsi memori dan kinerja saat bekerja dengan BLOB, tetapi sumber (stream atau file) tidak dapat diubah selama masa hidup instance Presentation.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```


Properti ini menentukan apakah file sementara dapat dibuat saat bekerja dengan BLOB, yang secara signifikan mengurangi konsumsi memori tetapi memerlukan izin untuk membuat file.

--------------------

Semua file akan dihapus setelah pekerjaan dengan presentasi selesai.

**Mengembalikan:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```


Properti ini menentukan apakah file sementara dapat dibuat saat bekerja dengan BLOB, yang secara signifikan mengurangi konsumsi memori tetapi memerlukan izin untuk membuat file.

--------------------

Semua file akan dihapus setelah pekerjaan dengan presentasi selesai.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```


Jalur akar tempat file sementara akan dibuat. Direktori sementara sistem akan digunakan secara default. Proses hosting harus memiliki izin untuk membuat file dan folder di sana.

**Mengembalikan:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```


Jalur akar tempat file sementara akan dibuat. Direktori sementara sistem akan digunakan secara default. Proses hosting harus memiliki izin untuk membuat file dan folder di sana.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```


Menentukan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB di memori. Secara default, semua BLOB dimuat ke memori; hanya ketika batas ini tercapai mekanisme alternatif (seperti file sementara) akan digunakan. Menyimpan BLOB di memori memaksimalkan kinerja tetapi dapat menyebabkan penggunaan memori yang tinggi. Gunakan properti ini untuk menyesuaikan perilaku dengan lingkungan atau persyaratan Anda.

--------------------

Properti ini diabaikan jika \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) disetel ke false, karena memori kemudian menjadi satu-satunya lokasi penyimpanan yang tersedia dan membatasi penggunaan BLOB di memori tidak berpengaruh.

--------------------

Nilai default adalah 629.145.600 byte (600 MB).

--------------------

Anda dapat menyetel properti ini ke nol, tetapi sejumlah kecil memori minimum tetap akan dipertahankan.

**Mengembalikan:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```


Menentukan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB di memori. Secara default, semua BLOB dimuat ke memori; hanya ketika batas ini tercapai mekanisme alternatif (seperti file sementara) akan digunakan. Menyimpan BLOB di memori memaksimalkan kinerja tetapi dapat menyebabkan penggunaan memori yang tinggi. Gunakan properti ini untuk menyesuaikan perilaku dengan lingkungan atau persyaratan Anda.

--------------------

Properti ini diabaikan jika \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) disetel ke false, karena memori kemudian menjadi satu-satunya lokasi penyimpanan yang tersedia dan membatasi penggunaan BLOB di memori tidak berpengaruh.

--------------------

Nilai default adalah 629.145.600 byte (600 MB).

--------------------

Anda dapat menyetel properti ini ke nol, tetapi sejumlah kecil memori minimum tetap akan dipertahankan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |