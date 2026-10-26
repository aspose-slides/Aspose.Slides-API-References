---
title: OperatingSystem
second_title: Aspose.Slides for C++ API Referenciája
description: "Egy adott operációs rendszert reprezentál, és információt nyújt róla. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new segítségével, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek."
type: docs
weight: 1171
url: /hu/system/operatingsystem/
---
## OperatingSystem osztály

Egy adott operációs rendszert reprezentál, és információkat nyújt róla. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat okozhat. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek.

```cpp
class OperatingSystem
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [PlatformID](../platformid/) [get_Platform](./get_platform/)() const | Visszaadja az aktuális objektum által reprezentált operációs rendszer platformazonosítóját. |
| [String](../string/) [get_ServicePack](./get_servicepack/)() const | Visszaadja az aktuális objektum által reprezentált operációs rendszer szolgáltatáscsomagjának nevét. |
| const [Version](../version/)\& [get_Version](./get_version/)() const | Visszaad egy konstans referenciát egy [Version](../version/) objektumra, amely az aktuális objektum által reprezentált operációs rendszer verzióját reprezentálja. |
| [String](../string/) [get_VersionString](./get_versionstring/)() const | Visszaadja az aktuális objektum által reprezentált operációs rendszer verziójának karakterlánc ábrázolását. |
| static **bool** [IsFreeBSD](./isfreebsd/)() | Jelzi, hogy az aktuális alkalmazás FreeBSD-n fut-e. |
| static **bool** [IsLinux](./islinux/)() | Jelzi, hogy az aktuális alkalmazás Linuxon fut-e. |
| static **bool** [IsMacOS](./ismacos/)() | Jelzi, hogy az aktuális alkalmazás MacOS-en fut-e. |
| static **bool** [IsOSPlatform](./isosplatform/)(const [String](../string/)\&) | Jelzi, hogy az aktuális alkalmazás a megadott platformon fut-e. |
| static **bool** [IsWindows](./iswindows/)() | Jelzi, hogy az aktuális alkalmazás a(z) [Windows](../../system.windows/) rendszeren fut-e. |
| [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&) | Létrehoz egy példányt, amely egy adott platformazonosítóval és verzióval megadott operációs rendszert reprezentál. |
| [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&, const [String](../string/)\&) | Létrehoz egy példányt, amely egy adott platformazonosítóval, verzióval és szolgáltatáscsomaggal megadott operációs rendszert reprezentál. |
| [String](../string/) [ToString](./tostring/)() const | Visszaadja az aktuális objektum által reprezentált operációs rendszer verziójának karakterlánc ábrázolását. |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)