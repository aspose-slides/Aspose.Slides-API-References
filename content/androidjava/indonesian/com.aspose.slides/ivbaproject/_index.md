---
title: IVbaProject
second_title: Aspose.Slides untuk Android via Java API Reference
description: Mewakili proyek VBA dengan makro presentasi.
type: docs
url: /id/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

Mewakili proyek VBA dengan makro presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getName()](#getName--) | Mengembalikan nama proyek VBA. |
| [getModules()](#getModules--) | Mengembalikan daftar semua modul yang terkandung dalam proyek VBA. |
| [getReferences()](#getReferences--) | Mengembalikan daftar semua referensi yang terkandung dalam proyek VBA. |
| [toBinary()](#toBinary--) | Mengembalikan representasi biner proyek VBA sebagai kontainer OLE. |
| [isPasswordProtected()](#isPasswordProtected--) | Menunjukkan apakah VBAProject dilindungi oleh kata sandi untuk melihat properti proyek. |
### getName() {#getName--}
```
public abstract String getName()
```


Mengembalikan nama proyek VBA. Baca-saja String.

**Mengembalikan:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```


Mengembalikan daftar semua modul yang terkandung dalam proyek VBA. Baca-saja [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Mengembalikan:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```


Mengembalikan daftar semua referensi yang terkandung dalam proyek VBA. Baca-saja [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Mengembalikan:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```


Mengembalikan representasi biner proyek VBA sebagai kontainer OLE. Baca-saja byte[].

**Mengembalikan:**
byte[] - Representasi biner proyek VBA sebagai kontainer OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


Menunjukkan apakah VBAProject dilindungi oleh kata sandi untuk melihat properti proyek. Baca-saja boolean.

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