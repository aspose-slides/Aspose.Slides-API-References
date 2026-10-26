---
title: VbaProject
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili proyek VBA dengan makro presentasi.
type: docs
url: /id/com.aspose.slides/vbaproject/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

Mewakili proyek VBA dengan makro presentasi.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [VbaProject()](#VbaProject--) | Konstruktor ini membuat proyek VBA baru dari awal. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | Konstruktor ini memuat proyek VBA dari representasi biner kontainer OLE. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getName()](#getName--) | Mengembalikan nama proyek VBA. |
| [getModules()](#getModules--) | Mengembalikan daftar semua modul yang terdapat dalam proyek VBA. |
| [getReferences()](#getReferences--) | Mengembalikan daftar semua referensi yang terdapat dalam proyek VBA. |
| [toBinary()](#toBinary--) | Mengembalikan representasi biner proyek VBA sebagai kontainer OLE |
| [isPasswordProtected()](#isPasswordProtected--) | Menunjukkan apakah VBAProject dilindungi oleh kata sandi untuk melihat properti proyek. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```


Konstruktor ini membuat proyek VBA baru dari awal. Proyek akan dibuat dalam codepage 1252 Windows Latin 1 (ANSI)

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```


Konstruktor ini memuat proyek VBA dari representasi biner kontainer OLE.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```


Mengembalikan nama proyek VBA. Read-only String.

**Mengembalikan:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```


Mengembalikan daftar semua modul yang terdapat dalam proyek VBA. Read-only [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Mengembalikan:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```


Mengembalikan daftar semua referensi yang terdapat dalam proyek VBA. Read-only [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Mengembalikan:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```


Mengembalikan representasi biner proyek VBA sebagai kontainer OLE

**Mengembalikan:**
byte[] - Representasi biner proyek VBA sebagai kontainer OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Menunjukkan apakah VBAProject dilindungi oleh kata sandi untuk melihat properti proyek. Read-only  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptm");
>  try {
>      if (presentation.getVbaProject().isPasswordProtected())
>          System.out.println("The VBAProject '" + presentation.getVbaProject().getName() +
>              "' is protected by password to view project properties.");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Mengembalikan:**
boolean