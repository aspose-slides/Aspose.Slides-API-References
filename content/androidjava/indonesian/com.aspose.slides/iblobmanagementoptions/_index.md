---
title: IBlobManagementOptions
second_title: Aspose.Slides for Android via Java API Reference
description: A Binary Large Object BLOB is a binary data stored as a single entity - i.e.
type: docs
url: /id/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Binary Large Object (BLOB) adalah data biner yang disimpan sebagai satu entitas tunggal - misalnya BLOB dapat berupa audio, video, atau presentasi itu sendiri. Berbagai teknik digunakan untuk mengoptimalkan konsumsi memori saat bekerja dengan BLOB — yang sudah disimpan dalam presentasi atau akan ditambahkan kemudian secara programatis. Menggunakan [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) Anda dapat mengubah berbagai aspek perilaku terkait penanganan BLOB untuk masa pakai instance [IPresentation](../../com.aspose.slides/ipresentation).
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Properti ini menentukan apakah sebuah instance dari kelas Presentation dapat menjadi pemilik sumber — file atau stream selama masa pakai instance. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Properti ini menentukan apakah sebuah instance dari kelas Presentation dapat menjadi pemilik sumber — file atau stream selama masa pakai instance. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Properti ini menentukan apakah file sementara dapat dibuat saat bekerja dengan BLOB, yang secara signifikan mengurangi konsumsi memori tetapi memerlukan izin untuk membuat file. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Properti ini menentukan apakah file sementara dapat dibuat saat bekerja dengan BLOB, yang secara signifikan mengurangi konsumsi memori tetapi memerlukan izin untuk membuat file. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Jalur root tempat file sementara akan dibuat. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Jalur root tempat file sementara akan dibuat. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Menentukan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB dalam memori. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Menentukan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB dalam memori. |
### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

Properti ini menentukan apakah sebuah instance dari kelas Presentation dapat menjadi pemilik sumber — file atau stream selama masa pakai instance. Jika instance menjadi pemilik, ia mengunci sumber tersebut. Ini membantu meningkatkan konsumsi memori dan kinerja saat bekerja dengan BLOB, namun sumber (stream atau file) tidak dapat diubah selama masa pakai instance Presentation. Berikut contoh:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException akan dilempar karena pres.pptx dikunci untuk masa pakai Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // setelah objek Presentation dibuang, file tidak terkunci lagi dan dapat dihapus
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
>  ```


**Mengembalikan:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

Properti ini menentukan apakah sebuah instance dari kelas Presentation dapat menjadi pemilik sumber — file atau stream selama masa pakai instance. Jika instance menjadi pemilik, ia mengunci sumber tersebut. Ini membantu meningkatkan konsumsi memori dan kinerja saat bekerja dengan BLOB, namun sumber (stream atau file) tidak dapat diubah selama masa pakai instance Presentation. Berikut contoh:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException akan dilempar karena pres.pptx dikunci untuk masa pakai Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // setelah objek Presentation dibuang, file tidak terkunci lagi dan dapat dihapus
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
>  ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

Properti ini menentukan apakah file sementara dapat dibuat saat bekerja dengan BLOB, yang secara signifikan mengurangi konsumsi memori tetapi memerlukan izin untuk membuat file.

--------------------

Semua file akan dihapus setelah pekerjaan dengan presentasi selesai.

**Mengembalikan:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
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
public abstract String getTempFilesRootPath()
```

Jalur root tempat file sementara akan dibuat. Direktori sementara sistem akan digunakan secara default. Proses hosting harus memiliki izin untuk membuat file dan folder di sana.

**Mengembalikan:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

Jalur root tempat file sementara akan dibuat. Direktori sementara sistem akan digunakan secara default. Proses hosting harus memiliki izin untuk membuat file dan folder di sana.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Menentukan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB dalam memori. Secara default, semua BLOB dimuat ke dalam memori; hanya setelah batas ini tercapai mekanisme alternatif (seperti file sementara) akan digunakan. Menyimpan BLOB di memori memaksimalkan kinerja tetapi dapat menyebabkan penggunaan memori yang tinggi. Gunakan properti ini untuk menyesuaikan perilaku dengan lingkungan atau kebutuhan Anda.

--------------------

Properti ini diabaikan jika \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) disetel ke false, karena memori kemudian menjadi satu-satunya lokasi penyimpanan yang tersedia dan pembatasan penggunaan BLOB dalam memori tidak berpengaruh.

--------------------

Nilai default adalah 629.145.600 byte (600 MB).

--------------------

Anda dapat menyetel properti ini ke nol, tetapi sejumlah kecil memori minimum tetap akan dipertahankan.

**Mengembalikan:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

Menentukan ukuran total maksimum (dalam byte) yang dapat ditempati semua BLOB dalam memori. Secara default, semua BLOB dimuat ke dalam memori; hanya setelah batas ini tercapai mekanisme alternatif (seperti file sementara) akan digunakan. Menyimpan BLOB di memori memaksimalkan kinerja tetapi dapat menyebabkan penggunaan memori yang tinggi. Gunakan properti ini untuk menyesuaikan perilaku dengan lingkungan atau kebutuhan Anda.

--------------------

Properti ini diabaikan jika \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) disetel ke false, karena memori kemudian menjadi satu-satunya lokasi penyimpanan yang tersedia dan pembatasan penggunaan BLOB dalam memori tidak berpengaruh.

--------------------

Nilai default adalah 629.145.600 byte (600 MB).

--------------------

Anda dapat menyetel properti ini ke nol, tetapi sejumlah kecil memori minimum tetap akan dipertahankan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |