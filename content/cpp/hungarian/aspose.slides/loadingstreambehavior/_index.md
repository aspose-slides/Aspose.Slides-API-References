---
title: LoadingStreamBehavior
second_title: Aspose.Slides C++ API referencia
description: "A System::IO::Stream egy metódusnak átadva Binary Large Object (BLOB) (lásd IBlobManagementOptions leírása). Ennek a felsorolásnak az értékei meghatározzák, hogyan kell kezelni a System::IO::Stream-et, amikor átadják a metódusnak. Az igényektől függően különböző döntések hozhatók a leghatékonyabb viselkedés biztosításához."
type: docs
weight: 6735
url: /hu/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enum

A [System::IO::Stream](../../system.io/stream/) egy metódusnak átadva Binary Large Object (BLOB)-nak tekinthető (lásd [IBlobManagementOptions](../iblobmanagementoptions/) leírása). Ennek a felsorolásnak az értékei meghatározzák, hogyan kell kezelni a [System::IO::Stream](../../system.io/stream/)-t, amikor átadják a metódusnak. Az igényektől függően különböző döntések hozhatók a leghatékonyabb viselkedés biztosításához.

```cpp
enum class LoadingStreamBehavior
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | Az adatfolyam a végéig lesz beolvasva, majd felszabadítva - vagyis garantált, hogy ezt az adatfolyamot a [IPresentation](../ipresentation/) példány a jövőben nem fogja használni. Lezárható a klienskód által vagy bármilyen más módon felhasználható. |
| KeepLocked | 1 | Az adatfolyam a [IPresentation](../ipresentation/) objektumban lesz zárolva, vagyis az adatfolyam tulajdonjoga átkerül. A [IPresentation](../ipresentation/) objektum felelős lesz az adatfolyam helyes felszabadításáért, amikor ez az objektum magát is felszabadul. Ez a viselkedés rendkívül hasznos, ha nagy BLOB fájlt kell sorosítania (például nagy videót vagy hangot -lásd [IBlobManagementOptions](../iblobmanagementoptions/) leírását), és el akarja kerülni a fájl memóriába töltését vagy egyéb teljesítményproblémákat. Egyszerűen megnyithatja a [System::IO::FileStream](../../system.io/filestream/) a fájlhoz, és átadhatja egy metódusnak, a [LoadingStreamBehavior::KeepLocked](./) LoadingStreamBehavior kiválasztásával. |

## Lásd még

* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)