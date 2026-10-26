---
title: "System::Security"
second_title: Aspose.Slides C++ API referencia
description: 
type: docs
weight: 807
url: /hu/system.security/
---
## Osztályok

| Osztály | Leírás |
| --- | --- |
| [Details_SecurityException](./details_securityexception/) |  |
| [SecureString](./securestring/) | Secure string, olyan szöveget képvisel, amelyet bizalmasan kell kezelni. Ez az osztály NEM TÁNITJA TITKOSAN a belső adatokat. Ennek az osztálynak a példányait csak a [System::MakeObject()](../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a stack-en vagy az operator new használatával, mert ez időbeli hibákhoz és/vagy állítási hibákhoz vezethet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként való átadásra a függvényeknek. |
| [SecureStringMarshal](./securestringmarshal/) | Metódusok gyűjteménye a nem kezelt memória blokkok lefoglalásához és másolásához. |
| [SecurityElement](./securityelement/) | XML objektum modell a biztonsági objektum kódolásához. Nincs megvalósítva. Ennek az osztálynak a példányait csak a [System::MakeObject()](../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a stack-en vagy az operator new használatával, mert ez időbeli hibákhoz és/vagy állítási hibákhoz vezethet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként való átadásra a függvényeknek. |
## Tipedefiníciók

| Tipedef | Leírás |
| --- | --- |
| [SecurityException](./securityexception/) |  |
| [SecureStringPtr](./securestringptr/) | [SecureString](./securestring/) mutató típus. |